---
title: "Tandatangani Dokumen dengan Tanda Tangan Digital"
linkTitle: "Digital Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Pelajari manfaat menggunakan tanda tangan digital untuk menandatangani dokumen secara aman. Temukan cara menambahkan tanda tangan digital secara programatis di Python dengan petunjuk langkah demi langkah."
type: docs
url: /id/python-net/guides/esign-document-with-digital-signature/
is_root: false
weight: 70
---


## Introduction

Di era digital saat ini, memastikan keaslian dan integritas dokumen elektronik sangat penting. Salah satu metode yang sangat efektif untuk mencapainya adalah dengan menggunakan tanda tangan digital. Dalam panduan ini, kami akan menjelajahi dunia tanda tangan digital, menjelaskan apa itu, mengapa penting, dan bagaimana Anda dapat memanfaatkan GroupDocs.Signature for Python via .NET untuk secara mulus menandatangani elektronik dokumen Anda.

## What is a Digital Signature?

Tanda tangan digital adalah mekanisme kriptografi untuk memverifikasi keaslian dan integritas dokumen elektronik. Ini memberikan jaminan kuat bahwa dokumen berasal dari pengirim yang dikenal dan tidak diubah oleh sumber yang tidak berwenang. Tanda tangan digital biasanya diwakili oleh sertifikat yang berisi kunci pribadi (untuk menandatangani) dan kunci publik (untuk verifikasi). Berbagai standar kriptografi kunci publik, seperti format PFX, biasanya digunakan untuk tujuan ini.
Gambar di bawah ini menunjukkan bagaimana tampilan tanda tangan digital pada halaman dokumen PDF secara default.

![Digital](https://docs.groupdocs.com/signature/python-net/images/esign-document-with-digital-signature.png)

## Why Use Digital Signatures?

- **Enhanced Security:** Digital signatures provide a higher level of document security, making it extremely challenging for unauthorized parties to alter the content.
- **Authentication:** They offer a reliable way to verify the identity of the document sender.
- **Non-repudiation:** Digital signatures prevent senders from denying the authenticity of the signed document.

## How to Sign a Document with a Digital Signature

**[GroupDocs.Signature for Python via .NET](https://products.groupdocs.com/signature/python-net)** supports the creation of digital signatures based on existing PFX certificates. To specify various settings the library provides the [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) class that allows adjusting digital signature properties in the document:

* The [certificate_file_path](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_file_path/) or [certificate_stream](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/certificate_stream/) properties define the certificate source;
* The [password](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/password/) property specifies the certificate password;
* The [contact](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/contact/), [reason](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/reason/) and [location](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/location/) properties specify additional descriptions;
* The [visible](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/visible/) property specifies whether the signature should be visible on the document page or not;
* The [xad_es_type](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/xad_es_type/) property defines whether the e-signature should be of an XML Advanced Electronic Signature type (supported for spreadsheet documents).

Sertifikat yang kedaluwarsa dan belum valid ditolak: `sign` menghasilkan [`GroupDocsSignatureException`](/signature/python-net/groupdocs.signature/groupdocssignatureexception/) dengan pesan seperti "The signing certificate expired on ...". Untuk menandatangani dengan sertifikat tersebut tetap, setel `allow_expired` atau `allow_not_yet_valid` ke `True`.

### Follow these steps to sign your documents with a digital signature

1. Instal paket GroupDocs.Signature menggunakan pip:
```bash
pip install groupdocs-signature-net
```

2. Buat instance baru dari kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) dan berikan jalur dokumen sumber sebagai parameter konstruktor.
3. Instansiasi objek [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) dengan sertifikat yang diperlukan dan kata sandinya.
4. Panggil metode [Sign](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature/sign/) dari instance kelas [Signature](https://reference.groupdocs.com/signature/python-net/groupdocs.signature/signature) dan berikan [DigitalSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/digitalsignoptions/) kepadanya.

Contoh di bawah ini menunjukkan cara menandatangani dokumen PDF dengan e-tanda tangan digital menggunakan Python. Kami dapat menandatangani format dokumen lain yang didukung dengan cara yang sama.

{{< tabs "sign_with_digital_signature" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature():
    with Signature("sample.pdf") as signature:
        # Buat opsi tanda tangan digital dengan file sertifikat
        options = DigitalSignOptions("certificate.pfx")

        # Setel kata sandi sertifikat
        options.password = "1234567890"

        # Opsional: gambar yang menunjukkan tanda tangan pada halaman
        options.image_file_path = "signature.jpg"

        # Setel posisi tanda tangan
        options.left = 100
        options.top = 400

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_digital.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` adalah sertifikat contoh yang digunakan dalam contoh ini (kata sandi `1234567890`). Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_digital.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature/signed_digital.pdf)
{{< /tab >}}
{{< /tabs >}}

### Advanced Digital Signature Options

Anda dapat menyesuaikan tanda tangan digital lebih lanjut dengan opsi tambahan: ukuran tanda tangan pada halaman, serta kontak, alasan, dan lokasi yang disimpan di dalamnya:

{{< tabs "sign_with_digital_signature_advanced" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_digital_signature_advanced():
    with Signature("sample.pdf") as signature:
        # Berikan sertifikat dan gambar tampilan ke konstruktor
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"

        # Tampilkan tanda tangan pada halaman, pada posisi dan ukuran ini
        options.visible = True
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 100

        # Informasi yang disimpan dalam tanda tangan
        options.contact = "John Smith"
        options.reason = "Approval"
        options.location = "New York"

        result = signature.sign("signed_digital_advanced.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_digital_signature_advanced()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` adalah sertifikat contoh yang digunakan dalam contoh ini (kata sandi `1234567890`). Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signature.jpg\" >}}

`signature.jpg` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/signature.jpg) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_digital_advanced.pdf" >}}
```text
Binary file (PDF, 616 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_digital_signature_advanced/signed_digital_advanced.pdf)
{{< /tab >}}
{{< /tabs >}}

### Loading Certificate from Stream

Anda juga dapat memuat sertifikat dari aliran. Biarkan aliran tetap terbuka hingga `sign` mengembalikan nilai:

{{< tabs "sign_with_certificate_from_stream" >}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

def sign_with_certificate_from_stream():
    with Signature("sample.pdf") as signature:
        # Muat sertifikat dari aliran
        with open("certificate.pfx", "rb") as certificate_stream:
            options = DigitalSignOptions(certificate_stream)
            options.password = "1234567890"

            # Atur posisi dan ukuran tanda tangan
            options.left = 100
            options.top = 400
            options.width = 200
            options.height = 60

            result = signature.sign("signed_digital_stream.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")

if __name__ == "__main__":
    sign_with_certificate_from_stream()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab "certificate.pfx" >}}

`certificate.pfx` adalah sertifikat contoh yang digunakan dalam contoh ini (kata sandi `1234567890`). Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/certificate.pfx) untuk mengunduhnya.

{{< /tab >}}
{{< tab "signed_digital_stream.pdf" >}}
```text
Binary file (PDF, 612 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/developer-guide/basic-usage/electronic-signature-types/esign-document-with-digital-signature/sign_with_certificate_from_stream/signed_digital_stream.pdf)
{{< /tab >}}
{{< /tabs >}}

### Summary
Panduan ini menunjukkan cara menggunakan [**GroupDocs.Signature for Python via .NET**](https://products.groupdocs.com/signature/python-net) untuk menandatangani dokumen dengan tanda tangan digital. Panduan ini menjelaskan cara memuat dokumen, mengonfigurasi tanda tangan berbasis sertifikat, dan menyimpan file yang ditandatangani secara aman. Fitur lanjutan, seperti tampilan tanda tangan dan informasi yang disimpan dalam tanda tangan, juga dibahas. Lihat sumber daya terkait untuk detail tambahan tentang alur kerja penandatanganan digital.

## More Resources

### GitHub Examples

Anda dapat dengan mudah menjalankan kode di atas dan melihat fitur ini beraksi dalam contoh GitHub kami:

* [GroupDocs.Signature for Python via .NET examples](https://github.com/groupdocs-signature/GroupDocs.Signature-for-Python-via-.NET)

### Free Online Apps

Bersamaan dengan pustaka Python yang lengkap, kami menyediakan aplikasi daring gratis yang sederhana namun kuat.

Untuk menandatangani PDF, Word, Excel, PowerPoint, dan dokumen lainnya, Anda dapat menggunakan aplikasi online dari **[GroupDocs.Signature App Product Family](https://products.groupdocs.app/signature/family)**.
