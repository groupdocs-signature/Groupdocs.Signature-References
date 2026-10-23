---
title: "eSign Dokumen dengan Tanda Tangan Kode QR"
linkTitle: "QR Code Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Artikel ini menjelaskan cara menandatangani dokumen dengan tanda tangan elektronik berupa kode QR pada halaman dokumen menggunakan GroupDocs.Signature untuk Python melalui .NET API."
type: docs
url: /id/python-net/guides/esign-document-with-qr-code-signature/
is_root: false
weight: 60
---


## What is a QR Code?

QR code (atau Quick Response code) adalah jenis [barcode](/signature/python-net/guides/esign-document-with-barcode-signature/) dua dimensi yang terdiri dari kotak hitam yang disusun dalam grid persegi pada latar belakang putih. QR code dapat dibaca oleh kamera smartphone atau perangkat khusus yang didedikasikan untuk membaca QR – pemindai genggam, terminal praktis, pemindai desktop, pemindai terintegrasi, dan sebagainya. Biasanya QR code berisi data yang mengarah ke situs web atau aplikasi, email, atau nomor telepon, pengidentifikasi produk, atau pelacak. Oleh karena itu, cakupan aplikasi QR code meluas dari pemasaran umum dan identifikasi barang hingga manajemen dokumen.

![QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature.png)

## How to eSign Document with QR-Code Signature

[**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) can sign the documents with QR codes of the following types. 

|  | Kode Aztec | Kode DataMatrix | GS1 DataMatrix | GS1 QR code | QR |
| --- | --- | --- | --- | --- | --- |
| **Aplikasi** | * transportasi dan tiket;<br> * dalam industri maskapai penerbangan untuk boarding pass elektronik;<br> * dalam kereta untuk tiket yang dijual secara online dan dicetak oleh pelanggan atau ditampilkan di layar ponsel. Kode dipindai oleh pemindai genggam oleh staf di kereta atau di pintu masuk untuk memvalidasi tiket.<br> * kedokteran - gelang identifikasi pasien dan label untuk obat satuan penggunaan, dll. | * media cetak seperti label dan surat;<br> * tujuan rekayasa industri - penandaan komponen, dll;<br>  * industri makanan - untuk mencegah produk makanan dikemas dan diberi tanggal secara tidak tepat; | Digunakan dalam<br> * Kesehatan;<br> * Pemerintahan;<br> * Industri.<br> Mengkodekan informasi tambahan item, seperti:<br> * berat;<br> * tanggal kedaluwarsa;<br> * nomor batch;<br> * tanggal produksi;<br> * dll. | Digunakan dalam pemasaran untuk mengkodekan informasi tambahan item pada kemasan | Secara luas digunakan dalam industri otomotif dan aplikasi seluler. Berguna untuk mengkodekan sejumlah besar karakter data dan URL tertentu. |
| **Panjang** | 3067 alfanumerik,<br> 3832 numerik,<br> 1914 byte | 2335 alfanumerik,<br> 3116 numerik | 2335 alfanumerik,<br> 3116 numerik,<br> 1556 byte | 7089 alfanumerik,<br> 4296 numerik,<br> 2953 byte | 4296 alfanumerik,<br> 7089 numerik,<br> 2953 byte |
|  | **Example** | ![Aztec](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_1.png) | ![DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_2.png) | ![GS1 DataMatrix](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_3.png) | ![GS1 QR code](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_4.png) | ![QR](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-qr-code-signature_5.png) |

Saat menambahkan tanda tangan elektronik kode QR ke dokumen, pengaturan utama adalah teks yang akan dikodekan dan [tipe kode QR](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.domain/qrcodetypes/#fields) yang harus ditentukan melalui kelas [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions).

Berikut langkah-langkah untuk eSign sebuah dokumen dengan tanda tangan kode QR:

* Create a new instance of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class and pass the source document path as a constructor parameter.

* Instantiate the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) object according to your requirements and specify the [encode_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions/encode_type) and [text](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/text) properties.
  
* Call the [sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) method of the [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) class instance and pass the [QrCodeSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/qrcodesignoptions) to it.

Potongan kode di bawah ini menunjukkan cara menandatangani dokumen PDF dengan tanda tangan kode QR menggunakan Python:

{{< tabs \"sign_with_qr_code_signature\" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

def sign_with_qr_code_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan kode QR dengan teks yang akan dikodekan
        options = QrCodeSignOptions("John Smith")

        # Atur tipe kode QR
        options.encode_type = QrCodeTypes.QR

        # Atur posisi dan ukuran kode QR
        options.left = 100
        options.top = 400
        options.width = 100
        options.height = 100

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_qr_code.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_qr_code.pdf" >}}
```text
Binary file (PDF, 57 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature/signed_qr_code.pdf)
{{< /tab >}}
{{< /tabs >}}

Jenis QR code lainnya dari tabel di atas diatur dengan cara yang sama, misalnya `QrCodeTypes.AZTEC` atau `QrCodeTypes.DATA_MATRIX`.

### Advanced QR Code Options

Berikut contoh yang menunjukkan cara membuat tanda QR code yang lebih kompleks dengan penyesuaian tambahan: perataan dan margin, warna modul, latar belakang, dan batas:

{{< tabs "sign_with_qr_code_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import (
    Background, Border, DashStyle, HorizontalAlignment, Padding,
    QrCodeTypes, VerticalAlignment)
from groupdocs.pydrawing import Color

def sign_with_qr_code_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Berikan teks dan tipe QR code ke konstruktor
        options = QrCodeSignOptions("https://www.example.com/verify-document", QrCodeTypes.QR)

        # Letakkan QR code di sudut kanan bawah halaman
        options.width = 120
        options.height = 120
        options.horizontal_alignment = HorizontalAlignment.RIGHT
        options.vertical_alignment = VerticalAlignment.BOTTOM
        options.margin = Padding(right=40, bottom=60)

        # Warna modul, latar belakang, dan batas titik dengan sedikit ruang di dalamnya
        options.fore_color = Color.dark_blue
        background = Background()
        background.color = Color.light_yellow
        options.background = background
        border = Border()
        border.color = Color.dark_blue
        border.dash_style = DashStyle.DOT
        border.weight = 2
        border.visible = True
        options.border = border
        options.inner_margins = Padding(4)

        result = signature.sign("signed_qr_code_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} QR code signature(s)")

if __name__ == "__main__":
    sign_with_qr_code_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_qr_code_advanced.pdf" >}}
```text
Binary file (PDF, 102 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-qr-code-signature/sign_with_qr_code_signature_advanced/signed_qr_code_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menunjukkan cara menambahkan tanda QR code ke dokumen menggunakan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net). Panduan ini mencakup langkah-langkah untuk menghasilkan tanda QR code, mengonfigurasi propertinya seperti ukuran dan enkoding, serta menerapkannya ke dokumen. Tanda QR code dapat digunakan untuk verifikasi cepat dokumen yang ditandatangani.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menghasilkan QR code dan/atau menandatangani file Anda dengan QR code secara gratis, Anda dapat menggunakan aplikasi daring [QR Code Generator](https://products.groupdocs.app/signature/generate/qrcode).

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi daring lainnya dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
