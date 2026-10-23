---
title: "Dokumen eSign dengan Tanda Tangan Teks"
linkTitle: "Text Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara menandatangani dokumen dengan tanda tangan Teks menggunakan GroupDocs.Signature for Python via .NET API. Pelajari cara menambahkan tanda tangan digital ke PDF secara programatis dengan Python."
type: docs
url: /id/python-net/guides/esign-document-with-text-signature/
is_root: false
weight: 30
---


## What is a Text Signature?

Sebuah tanda tangan elektronik **Text** adalah teks sembarang yang ditambahkan ke dokumen secara native tergantung pada jenis dokumen. GroupDocs.Signature menyediakan fitur tanda tangan teks dan memungkinkan penyesuaian berbagai pengaturan teks — mulai dari nama font, ukuran, dan warna hingga perataan, batas, efek bayangan, dll. Inilah contoh tampilan tanda tangan teks:

![Text](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-text-signature.png)

## How to eSign Document with Text Signature

Mari kita coba menambahkan tanda tangan teks ke PDF secara programatis menggunakan Python.

Untuk memanipulasi tanda tangan teks secara programatis, [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) menyediakan kelas [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) dan seluruh alur kerja menjadi semudah berikut:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) object according to your requirements and specify the signature options.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions) to it.

Contoh ini menunjukkan cara menambahkan tanda tangan teks ke dokumen menggunakan Python:

{{< tabs "sign_with_text_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import SignatureFont
from groupdocs.pydrawing import Color

def sign_with_text_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan teks
        options = TextSignOptions("John Smith")

        # Atur posisi dan ukuran tanda tangan
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 50

        # Atur warna teks dan font
        options.fore_color = Color.red
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 24
        options.font = font

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_text.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_text.pdf" >}}
```text
Binary file (PDF, 122 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature/signed_text.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Text Signature Options

Anda dapat menyesuaikan tanda tangan teks lebih lanjut dengan opsi tambahan: perataan dan margin, gaya font, latar belakang, batas, rotasi, dan transparansi. Ketika perataan diatur, itu menggantikan koordinat `left` atau `top`, dan `margin` menggeser tanda tangan dari tepi halaman.

{{< tabs "sign_with_text_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    SignatureFont, TextSignatureImplementation, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_text_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")

        # Letakkan tanda tangan di sudut kanan bawah halaman
        options.width = 220
        options.height = 60
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Gaya font dan warna teks
        font = SignatureFont()
        font.family_name = "Arial"
        font.size = 20
        font.bold = True
        font.italic = True
        options.font = font
        options.fore_color = Color.dark_blue

        # Latar belakang, batas, rotasi, dan transparansi
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        options.border = border
        options.rotation_angle = -10
        options.transparency = 0.2

        # Render teks sebagai gambar, yang juga menggambar batas pada halaman PDF
        options.signature_implementation = TextSignatureImplementation.IMAGE

        result = signature.sign("signed_text_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} text signature(s)")

if __name__ == "__main__":
    sign_with_text_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_text_advanced.pdf" >}}
```text
Binary file (PDF, 53 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-text-signature/sign_with_text_signature_advanced/signed_text_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menjelaskan cara menambahkan tanda tangan berbasis teks ke dokumen dengan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Panduan ini mencakup pengaturan properti teks seperti font, warna, ukuran, dan posisi, serta menerapkan tanda tangan teks ke sebuah dokumen. Dokumen yang ditandatangani kemudian disimpan dengan tanda tangan teks yang ditambahkan.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
