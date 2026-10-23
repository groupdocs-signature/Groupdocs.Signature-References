---
title: "eSign Dokumen dengan Banyak Tanda Tangan"
linkTitle: "Multiple Types eSign"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara menandatangani dokumen dengan banyak tanda tangan dari berbagai jenis oleh GroupDocs.Signature for Python via .NET API"
type: docs
url: /id/python-net/guides/esign-document-with-multiple-signatures/
is_root: false
weight: 80
---


[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) allows signing a document with several signatures simultaneously and even apply signatures of different types to the same document.

Melakukan ini semudah:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path or stream as a constructor parameter.
* Instantiate all required sign options objects depending on signature type:
    * [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) - for Barcode signatures;
    * [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) - for Digital signatures;
    * [FormFieldSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/formfieldsignoptions) - for Form-field signatures;
    * [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) - for Image signatures;
    * [MetadataSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/metadatasignoptions) - for Metadata signatures;
    * [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) - for QR-code signatures
    * [StampSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/stampsignoptions) - for Stamp signatures;
    * [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) - for Text signatures.
* Fill the collection with sign options from the previous step.  
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the collection of sign options to it.

Potongan kode di bawah ini menunjukkan cara eSign dokumen PDF dengan banyak tanda tangan secara bersamaan menggunakan Python:

{{< tabs "sign_with_multiple_signatures" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import (
    BarcodeSignOptions, DigitalSignOptions, QrCodeSignOptions, TextSignOptions)
from groupdocs.signature.domain import BarcodeTypes, QrCodeTypes

def sign_with_multiple_signatures():
    with Signature("sample.pdf") as signature:
        # Tentukan opsi tanda tangan teks
        text_options = TextSignOptions("This is test message")
        text_options.left = 100
        text_options.top = 360
        text_options.width = 200
        text_options.height = 30

        # Tentukan opsi tanda tangan barcode
        barcode_options = BarcodeSignOptions("123456")
        barcode_options.encode_type = BarcodeTypes.CODE128
        barcode_options.left = 100
        barcode_options.top = 420
        barcode_options.width = 200
        barcode_options.height = 60

        # Tentukan opsi tanda tangan kode QR
        qrcode_options = QrCodeSignOptions("JohnSmith")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.left = 100
        qrcode_options.top = 520
        qrcode_options.width = 100
        qrcode_options.height = 100

        # Tentukan opsi tanda tangan digital dengan sertifikat dan gambar tampilan
        digital_options = DigitalSignOptions("certificate.pfx")
        digital_options.password = "1234567890"
        digital_options.image_file_path = "signature.jpg"
        digital_options.left = 350
        digital_options.top = 520
        digital_options.width = 160
        digital_options.height = 100

        # Tandatangani dokumen dengan daftar opsi tanda tangan
        list_options = [text_options, barcode_options, qrcode_options, digital_options]
        result = signature.sign("signed_multiple.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` adalah sertifikat contoh yang digunakan dalam contoh ini (kata sandi `1234567890`). Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/certificate.pfx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_multiple.pdf" >}}
```text
Binary file (PDF, 740 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures/signed_multiple.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Multiple Signatures Example

Berikut contoh yang lebih maju yang menunjukkan cara menambahkan beberapa tanda tangan dengan gaya dan posisi yang berbeda. Setiap tanda tangan ditempatkan dengan perataan dan margin dari tepi halaman:

{{< tabs "sign_with_multiple_signatures_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions, QrCodeSignOptions, TextSignOptions
from groupdocs.signature.domain import (
    HorizontalAlignment, Padding, QrCodeTypes, SignatureFont, VerticalAlignment)

def sign_with_multiple_signatures_advanced():
    with Signature("sample.pdf") as signature:
        # Tanda tangan teks tebal di kanan atas, di bawah header halaman
        text_options = TextSignOptions("Approved by John Smith")
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        text_options.font = font
        text_options.width = 280
        text_options.height = 40
        text_options.vertical_alignment = VerticalAlignment.TOP
        text_options.horizontal_alignment = HorizontalAlignment.RIGHT
        text_options.margin = Padding(top=170, right=20)

        # Gambar stempel di pojok kiri bawah
        image_options = ImageSignOptions("stamp.png")
        image_options.width = 100
        image_options.height = 100
        image_options.vertical_alignment = VerticalAlignment.BOTTOM
        image_options.horizontal_alignment = HorizontalAlignment.LEFT
        image_options.margin = Padding(left=20, bottom=20)

        # Kode QR di pojok kanan bawah
        qrcode_options = QrCodeSignOptions("https://www.example.com/verify")
        qrcode_options.encode_type = QrCodeTypes.QR
        qrcode_options.width = 100
        qrcode_options.height = 100
        qrcode_options.vertical_alignment = VerticalAlignment.BOTTOM
        qrcode_options.horizontal_alignment = HorizontalAlignment.RIGHT
        qrcode_options.margin = Padding(right=20, bottom=20)

        # Tandatangani dokumen dengan daftar opsi tanda tangan
        list_options = [text_options, image_options, qrcode_options]
        result = signature.sign("signed_multiple_advanced.pdf", list_options)
        print(f"Signed with {len(result.succeeded)} signatures:")
        for item in result.succeeded:
            print(f"  {item.signature_type.name}")

if __name__ == "__main__":
    sign_with_multiple_signatures_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "stamp.png" >}}

`stamp.png` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/stamp.png) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_multiple_advanced.pdf" >}}
```text
Binary file (PDF, 178 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-multiple-signatures/sign_with_multiple_signatures_advanced/signed_multiple_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menunjukkan cara menerapkan beberapa jenis tanda tangan elektronik (mis., teks, barcode, gambar) ke dokumen menggunakan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Panduan ini menjelaskan cara menggabungkan berbagai jenis tanda tangan, mengonfigurasi masing‑masing, dan menyimpan dokumen yang ditandatangani dengan beberapa gaya tanda tangan.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
