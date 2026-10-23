---
title: "Hasilkan pratinjau tanda tangan"
linkTitle: "Generate signatures preview"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Topik ini menjelaskan cara menghasilkan pratinjau tanda tangan dokumen dalam Python dengan berbagai opsi oleh GroupDocs.Signature for Python via .NET."
type: docs
url: /id/python-net/guides/generate-signatures-preview/
is_root: false
weight: 120
---


## Overview

[**GroupDocs.Signature**](https://products.groupdocs.com/signature/python-net) provides [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) class to generate an image of a signature before it is placed on a document - for example, to show a user what a text, barcode or QR code signature will look like.

Berikut langkah-langkah untuk menghasilkan pratinjau tanda tangan dengan GroupDocs.Signature:

* Create the sign options that describe the signature, for example [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/) or [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/). No document is needed.
* Instantiate the [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) object with:
* the sign options;
* a function that creates the stream for the signature image (see [CreateSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/createsignaturestream/));
* image preview format - PNG / JPEG / BMP / GIF / SVG (PNG by default),
* an optional `signature_id` that tells the functions which signature they are handling.

Aliran yang dikembalikan oleh fungsi create ditutup secara otomatis segera setelah gambar tanda tangan ditulis: sebuah file ditutup, dan sebuah `io.BytesIO` sudah memegang gambar lengkap. Jika Anda perlu memproses gambar yang selesai atau membersihkan sumber daya sendiri, berikan fungsi release sebagai argumen tambahan (lihat [ReleaseSignatureStream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/releasesignaturestream/)).

* Call the static `generate_signature_preview` method of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/) class and pass [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) to it.

## CreateSignatureStream delegate implementation

GroupDocs.Signature memanggil fungsi create dengan objek [PreviewSignatureOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/previewsignatureoptions/) dan menulis gambar tanda tangan ke dalam aliran yang dikembalikannya: sebuah objek file yang dapat ditulis, sebuah `io.BytesIO`, atau aliran .NET.

```python
def create_signature_stream(preview_options):
    # Berikan nama gambar sesuai dengan signature_id yang ditetapkan pada opsi pratinjau
    return open(f"{preview_options.signature_id}.png", "wb")
```

## ReleaseSignatureStream delegate implementation

Fungsi release menerima opsi pratinjau yang sama dan objek yang sama yang dikembalikan oleh fungsi create. Pada saat fungsi tersebut dipanggil, gambar sudah lengkap.

```python
def release_signature_stream(preview_options, signature_stream):
    # signature_stream adalah objek yang dikembalikan oleh create_signature_stream
    print(f"Image file {signature_stream.name} is ready for preview")
```

## Generate signature preview to an image file

{{< tabs \"generate_signature_preview_to_file\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.pydrawing import Color
from groupdocs.signature.domain import SignatureFont
from groupdocs.signature.options import PreviewSignatureOptions, TextSignOptions

def create_signature_stream(preview_options):
    # Berikan nama gambar sesuai dengan signature_id yang ditetapkan di bawah
    return open(f"{preview_options.signature_id}.png", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"Image file {signature_stream.name} is ready for preview")

def generate_signature_preview_to_file():
    # Jelaskan tanda tangan secara tepat seperti yang Anda lakukan untuk penandatanganan
    sign_options = TextSignOptions("John Smith")
    sign_options.width = 200
    sign_options.height = 50
    sign_options.fore_color = Color.dark_blue
    font = SignatureFont()
    font.family_name = "Arial"
    font.size = 24
    sign_options.font = font

    # Buat objek opsi pratinjau
    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
    preview_options.signature_id = "text_signature"
    preview_options.preview_format = PreviewSignatureOptions.PreviewFormats.PNG

    # Hasilkan pratinjau; tidak ada dokumen yang terlibat
    Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_preview_to_file()
```
{{< /tab >}}
{{< tab \"text_signature.png\" >}}
```text
Binary file (PNG, 983 bytes)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_file/text_signature.png)
{{< /tab >}}
{{< /tabs >}}

## Generate signature preview to a memory stream

Fungsi create dapat mengembalikan sebuah `io.BytesIO`. Ketika `generate_signature_preview` selesai, buffer menyimpan seluruh gambar, siap untuk disimpan atau dikirim ke tempat lain.

{{< tabs \"generate_signature_preview_to_memory\" >}}
{{< tab "Python" >}}
```python
import io

from groupdocs.signature import Signature
from groupdocs.signature.domain import QrCodeTypes
from groupdocs.signature.options import PreviewSignatureOptions, QrCodeSignOptions

def generate_signature_preview_to_memory():
    image = io.BytesIO()

    def create_signature_stream(preview_options):
        # Tulis gambar ke dalam buffer alih-alih ke file
        return image

    sign_options = QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR)
    sign_options.width = 120
    sign_options.height = 120

    preview_options = PreviewSignatureOptions(sign_options, create_signature_stream)
    Signature.generate_signature_preview(preview_options)

    data = image.getvalue()
    is_png = data.startswith(b"\x89PNG")
    print(f"QR code preview: {len(data)} bytes, PNG image: {is_png}")

if __name__ == "__main__":
    generate_signature_preview_to_memory()
```
{{< /tab >}}
{{< tab \"generate-signature-preview-to-memory.txt\" >}}
```text
QR code preview: 918 bytes, PNG image: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_preview_to_memory/generate-signature-preview-to-memory.txt)
{{< /tab >}}
{{< /tabs >}}

## Generate previews of several signatures in different formats

Satu pasangan fungsi dapat melayani sejumlah pratinjau: `signature_id` memberi tahu fungsi tersebut tanda tangan mana yang sedang diproses, dan `preview_format` memilih jenis gambar. Tanpa lisensi, format SVG hanya tersedia untuk kode batang Code39.

{{< tabs \"generate_signature_previews_in_different_formats\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes
from groupdocs.signature.options import BarcodeSignOptions, PreviewSignatureOptions, QrCodeSignOptions

FORMATS = PreviewSignatureOptions.PreviewFormats

def create_signature_stream(preview_options):
    extension = preview_options.preview_format.name.lower()
    return open(f"{preview_options.signature_id}.{extension}", "wb")

def release_signature_stream(preview_options, signature_stream):
    print(f"{preview_options.signature_id}: {signature_stream.name}")

def generate_signature_previews_in_different_formats():
    signatures = [
        ("barcode", BarcodeSignOptions("123456789012", BarcodeTypes.CODE128), FORMATS.JPEG),
        ("qr_code", QrCodeSignOptions("https://www.groupdocs.com/", QrCodeTypes.QR), FORMATS.GIF),
        ("barcode_vector", BarcodeSignOptions("GROUPDOCS", BarcodeTypes.CODE39), FORMATS.SVG),
    ]
    for signature_id, sign_options, preview_format in signatures:
        preview_options = PreviewSignatureOptions(sign_options, create_signature_stream, release_signature_stream)
        preview_options.signature_id = signature_id
        preview_options.preview_format = preview_format
        Signature.generate_signature_preview(preview_options)

if __name__ == "__main__":
    generate_signature_previews_in_different_formats()
```
{{< /tab >}}
{{< tab \"generate-signature-previews-in-different-formats-outputs.zip\" >}}
```text
barcode.jpeg (8 KB)
barcode_vector.svg (3 KB)
qr_code.gif (4 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/generate-signatures-preview/generate_signature_previews_in_different_formats/generate-signature-previews-in-different-formats-outputs.zip)
{{< /tab >}}
{{< /tabs >}}

## More resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python examples, plugins, and showcase](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
