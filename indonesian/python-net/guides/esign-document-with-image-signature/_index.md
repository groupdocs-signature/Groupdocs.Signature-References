---
title: "Dokumen eSign dengan Tanda Tangan Gambar"
linkTitle: "Image Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menunjukkan cara menambahkan gambar tanda tangan pada halaman dokumen dengan GroupDocs.Signature untuk Python melalui .NET."
type: docs
url: /id/python-net/guides/esign-document-with-image-signature/
is_root: false
weight: 40
---


## What is an Image Signature?

Sebuah **image** sebagai tanda tangan adalah cara alternatif untuk menampilkan data apa pun dalam bentuk visual. Jenis tanda tangan elektronik ini memungkinkan pembuatan gambar khusus dengan logo perusahaan, inisial pengirim, nama, dan sebagainya.

![Images](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-image-signature.png)

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) provides the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) class to specify different settings for image signature such as image content by file or stream, location, colors and advanced effects.

Berikut langkah-langkah untuk membuat tanda tangan gambar pada halaman dokumen:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter;
* Instantiate the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) object according to your requirements and specify Image signature options;
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [ImageSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/imagesignoptions) to it.

## How to eSign Document with Image Signature

Contoh ini menunjukkan cara menandatangani dokumen PDF dengan tanda tangan gambar menggunakan Python:

{{< tabs \"sign_with_image_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan gambar dengan file gambar
        options = ImageSignOptions("signature.jpg")

        # Atur posisi dan ukuran tanda tangan
        options.left = 100
        options.top = 400
        options.width = 120
        options.height = 100

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_image.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signed_image.pdf\" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature/signed_image.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Image Signature Options

Anda dapat menyesuaikan tanda tangan gambar lebih lanjut dengan opsi tambahan: perataan dan margin, rotasi, transparansi, serta border. Ketika perataan diatur, itu menggantikan koordinat `left` atau `top`, dan `margin` menggeser tanda tangan dari tepi halaman.

{{< tabs \"sign_with_image_signature_advanced\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions
from groupdocs.signature.domain import (
    Border, DashStyle, HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_image_signature_advanced():
    with Signature("sample.pdf") as signature:
        options = ImageSignOptions("signature.jpg")

        # Letakkan tanda tangan di sudut kanan bawah halaman
        options.width = 160
        options.height = 136
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Putar gambar dan buat menjadi 20% transparan
        options.rotation_angle = 10
        options.transparency = 0.2

        # Gambar border bergaris putus-putus di sekitar gambar
        border = Border()
        border.color = Color.dark_green
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border

        result = signature.sign("signed_image_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signed_image_advanced.pdf\" >}}
```text
Binary file (PDF, 55 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_signature_advanced/signed_image_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Image from Stream

Anda juga dapat memuat gambar tanda tangan dari aliran. Biarkan aliran tetap terbuka sampai `sign` mengembalikan nilai:

{{< tabs "sign_with_image_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

def sign_with_image_from_stream():
    with Signature("sample.pdf") as signature:
        # Muat gambar tanda tangan dari aliran
        with open("signature.jpg", "rb") as image_stream:
            options = ImageSignOptions(image_stream)
            options.left = 100
            options.top = 400
            options.width = 120
            options.height = 100

            result = signature.sign("signed_image_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} image signature(s)")

if __name__ == "__main__":
    sign_with_image_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_image_stream.pdf" >}}
```text
Binary file (PDF, 40 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-image-signature/sign_with_image_from_stream/signed_image_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menunjukkan cara menggunakan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) untuk menambahkan tanda tangan berbasis gambar ke dokumen. Panduan ini mencakup memuat dokumen, mengonfigurasi properti tanda tangan gambar (seperti ukuran, posisi, dan transparansi), serta menyimpan dokumen yang telah ditandatangani. Opsi penyesuaian lanjutan, seperti mengatur tampilan gambar dan menyelaraskan tanda tangan, juga dibahas. Untuk wawasan lebih lanjut, jelajahi sumber daya penandatanganan dokumen terkait.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menghasilkan tanda tangan gambar dan/atau menandatangani file Anda dengan mereka secara gratis, Anda dapat menggunakan aplikasi daring [Generate Image](https://products.groupdocs.app/signature/generate/image).

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi daring lainnya dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
