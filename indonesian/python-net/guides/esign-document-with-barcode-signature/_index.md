---
title: "Tanda Tangan Elektronik Dokumen dengan Tanda Tangan Barcode"
linkTitle: "Barcode Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara menambahkan tanda tangan Barcode pada halaman dokumen dengan berbagai opsi seperti jenis barcode, teks barcode, penempatan, perataan, dan pengaturan visual lainnya menggunakan GroupDocs.Signature untuk Python melalui .NET"
type: docs
url: /id/python-net/guides/esign-document-with-barcode-signature/
is_root: false
weight: 50
---


## What is a Barcode?

Sebuah **barcode** atau **bar code** adalah cara menyajikan data dalam bentuk visual yang dapat dibaca mesin. Secara umum, barcode adalah gambar berbentuk persegi panjang yang terdiri dari garis hitam paralel dan ruang putih dengan lebar yang berbeda.
Barcode digunakan di berbagai bidang di mana identifikasi cepat diperlukan — sebagai bagian dari proses pembelian di toko ritel, di gudang untuk melacak persediaan, dan pada faktur untuk membantu akuntansi, serta banyak penggunaan lainnya.

![Barcode](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-barcode-signature.gif)

Barcode memungkinkan penyimpanan data terkait produk seperti tanggal produksi dan kedaluwarsa, nama produsen, negara asal, serta harga produk. Saat ini terdapat banyak jenis barcode karena perusahaan yang berbeda menggunakan kombinasi angka dan garis yang berbeda dalam barcode mereka sesuai kebutuhan. Dari perspektif tanda tangan dokumen, Barcode dapat berisi karakter yang berbeda (huruf, angka, atau simbol) dan dapat memiliki panjang serta ukuran yang beragam tergantung pada jenis dan pengaturannya untuk menyimpan informasi tanda tangan, judul, subjek, atau data terenkripsi singkat.

## How to eSign Document with Barcode Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) supports a wide range of Barcode types that can be used to create electronic signatures within the documents. Please refer to the [BarcodeTypes](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/barcodetypes/#fields) description to get the full list of supported barcodes.  
Untuk menentukan opsi yang berbeda bagi tanda tangan Barcode, GroupDocs.Signature untuk Python melalui .NET menyediakan kelas [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions). Bidang utama adalah:

* [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) - specifies the Barcode type (AustralianPost, Codabar, EAN13, OPC, etc.);
* [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) - specifies the Barcode text.

Berikut langkah-langkah untuk menandatangani elektronik sebuah dokumen dengan tanda tangan Barcode menggunakan GroupDocs.Signature untuk Python melalui API .NET:
* Create a new instance of [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.
* Instantiate the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) object according to your requirements and specify the Barcode type by setting the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions/encode_type) property with one of the predefined supported types. Set the [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) property value.
* Call the [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [BarcodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/barcodesignoptions) to it.

Contoh ini menunjukkan cara menandatangani dokumen PDF dengan tanda tangan Barcode menggunakan Python:

{{< tabs "sign_with_barcode_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_barcode_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan barcode dengan teks yang akan dienkode
        options = BarcodeSignOptions("John Smith")

        # Atur jenis barcode
        options.encode_type = BarcodeTypes.CODE128

        # Atur posisi dan ukuran barcode
        options.left = 100
        options.top = 400
        options.width = 300
        options.height = 100

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_barcode.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_barcode.pdf" >}}
```text
Binary file (PDF, 49 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature/signed_barcode.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Barcode Signature Options

Anda dapat menyesuaikan tanda tangan barcode lebih lanjut dengan opsi tambahan: perataan dan margin, warna bar, posisi teks yang dienkode, margin dalam, latar belakang, batas, dan transparansi:

{{< tabs "sign_with_barcode_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import (
    Background, BarcodeTypes, Border, CodeTextAlignment, DashStyle,
    HorizontalAlignment, Padding, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_barcode_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Berikan teks dan jenis barcode ke konstruktor
        options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)

        # Letakkan barcode di sudut kanan bawah halaman
        options.width = 220
        options.height = 80
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Warna bar, teks yang dienkode di bawah bar, ruang di dalam batas
        options.fore_color = Color.dark_blue
        options.code_text_alignment = CodeTextAlignment.BELOW
        options.inner_margins = Padding(5)

        # Latar belakang, batas, dan transparansi
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DASH
        border.weight = 2
        border.visible = True
        options.border = border
        options.transparency = 0.2

        result = signature.sign("signed_barcode_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} barcode signature(s)")

if __name__ == "__main__":
    sign_with_barcode_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_barcode_advanced.pdf" >}}
```text
Binary file (PDF, 58 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_barcode_signature_advanced/signed_barcode_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Different Barcode Types

GroupDocs.Signature mendukung berbagai jenis barcode. Setiap jenis menerima kumpulan karakter dan panjangnya masing-masing, jadi pilih teks yang sesuai dengan jenisnya. Contoh ini menandatangani sebuah dokumen dengan empat barcode dari jenis yang berbeda dalam satu panggilan:

{{< tabs "sign_with_different_barcode_types" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

def sign_with_different_barcode_types():
    barcodes = [
        (BarcodeTypes.EAN13, "123456789012"),            # 12 digits, check digit added
        (BarcodeTypes.CODE39, "JOHN SMITH"),             # upper-case letters, digits
        (BarcodeTypes.CODE128, "John Smith"),            # any ASCII text
        (BarcodeTypes.PDF417, "John Smith, approved"),   # 2D barcode for longer text
    ]

    # Satu objek opsi tanda tangan per barcode, ditempatkan satu di bawah yang lain
    options_list = []
    for index, (encode_type, text) in enumerate(barcodes):
        options = BarcodeSignOptions(text, encode_type)
        options.left = 100
        options.top = 340 + index * 100
        options.width = 240
        options.height = 80
        options_list.append(options)

    with Signature("sample.pdf") as signature:
        result = signature.sign("signed_barcode_types.pdf", options_list)
        for barcode in result.succeeded:
            print(f"{barcode.encode_type.type_name}: {barcode.text}")

if __name__ == "__main__":
    sign_with_different_barcode_types()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signed_barcode_types.pdf\" >}}
```text
Binary file (PDF, 78 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-barcode-signature/sign_with_different_barcode_types/signed_barcode_types.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menunjukkan cara menggunakan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) untuk menambahkan tanda tangan berbasis kode batang ke dokumen. Panduan ini mencakup pembuatan, konfigurasi, dan penerapan tanda tangan kode batang dengan dukungan untuk berbagai jenis kode batang serta opsi penyesuaian. Untuk eksplorasi lebih lanjut, lihat panduan terkait tentang informasi dokumen dan teknik penandatanganan lanjutan.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menghasilkan kode batang dan/atau menandatangani file Anda dengan kode batang secara gratis, Anda dapat menggunakan aplikasi daring [Barcode Generator](https://products.groupdocs.app/signature/generate/barcode).

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi daring lainnya dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
