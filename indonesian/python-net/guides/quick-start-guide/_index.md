---
title: "Panduan Memulai Cepat"
linkTitle: "Quick Start Guide"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Siapkan lingkungan virtual, instal groupdocs-signature-net, dan jalankan tiga contoh minimal: menandatangani PDF dengan tanda teks, mencari tanda di dalamnya, dan memverifikasinya."
type: docs
url: /id/python-net/guides/quick-start-guide/
is_root: false
weight: 20
---


Panduan ini memberikan gambaran singkat tentang cara menyiapkan dan mulai menggunakan GroupDocs.Signature untuk Python via .NET. Perpustakaan ini menambahkan, menemukan, memverifikasi, memperbarui, dan menghapus tanda elektronik dalam file PDF, Word, Excel, PowerPoint, OpenDocument, dan gambar dengan beberapa baris kode.

## Prerequisites

Untuk melanjutkan, pastikan Anda memiliki:

1. Lingkungan yang telah dikonfigurasi seperti dijelaskan dalam topik [System Requirements](https://docs.groupdocs.com/signature/python-net/system-requirements/). Pada Linux dan macOS ini mencakup beberapa paket sistem.
2. Opsional, sebuah [Temporary License](https://purchase.groupdocs.com/temporary-license/) untuk menguji semua fitur produk. Tanpa lisensi, perpustakaan beroperasi dalam mode evaluasi: ia memproses dokumen hingga dua halaman dan menambahkan baris evaluasi pada setiap halaman yang ditandatangani. Lihat [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/).

## Set Up Your Development Environment

Untuk praktik terbaik, gunakan lingkungan virtual untuk mengelola dependensi. Pelajari lebih lanjut di panduan [Create and Use Virtual Environments](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/#create-and-use-virtual-environments).

### Create and Activate a Virtual Environment

Buat lingkungan virtual:

{{< tabs "create-venv">}}
{{< tab "Windows" >}}
```ps
py -m venv .venv
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m venv .venv
```
{{< /tab >}}
{{< /tabs >}}

Aktifkan:

{{< tabs "activate-venv">}}
{{< tab "Windows" >}}
```ps
.venv\Scripts\activate
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
source .venv/bin/activate
```
{{< /tab >}}
{{< /tabs >}}

### Install the `groupdocs-signature-net` Package

{{< tabs "install-package">}}
{{< tab "Windows" >}}
```ps
py -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 -m pip install groupdocs-signature-net
```
{{< /tab >}}
{{< /tabs >}}

Lihat [Installation](/signature/python-net/guides/installation/) untuk menetapkan versi dan untuk menginstal tanpa akses ke PyPI.

## Example 1: Sign a PDF with a Text Signature

Buka sebuah dokumen, jelaskan tanda dengan [TextSignOptions](https://reference.groupdocs.com/signature/python-net/groupdocs.signature.options/textsignoptions/), dan simpan salinan yang telah ditandatangani.

{{< tabs "sign_pdf_with_text_signature">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf_with_text_signature():
    # Buka dokumen; blok with melepaskan file saat selesai
    with Signature("sample.pdf") as signature:
        # Tanda tangan teks 100 piksel dari tepi kiri dan atas halaman pertama
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100

        # Tandatangani dan simpan hasil ke file baru; sumber tetap tidak berubah
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")

if __name__ == "__main__":
    sign_pdf_with_text_signature()
```
{{< /tab >}}
{{< tab "sample.pdf" >}}

`sample.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/sample.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"signed_sample.pdf\" >}}
```text
Binary file (PDF, 125 KB)
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/sign_pdf_with_text_signature/signed_sample.pdf)
{{< /tab >}}
{{< /tabs >}}

## Example 2: Search a Document for Signatures

Temukan tanda tangan yang sudah dimiliki dokumen. `search` mengambil daftar opsi pencarian, satu per jenis tanda tangan yang dicari, dan mengembalikannya dalam `result.signatures`.

{{< tabs \"search_document_for_signatures\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

def search_document_for_signatures():
    with Signature("signed.pdf") as signature:
        # Cari tanda tangan teks pada setiap halaman
        result = signature.search([TextSearchOptions()])
        for found in result.signatures:
            print(f"Text signature '{found.text}' on page {found.page_number}")

if __name__ == "__main__":
    search_document_for_signatures()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"search-document-signatures.txt\" >}}
```text
Text signature 'John Smith' on page 1
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/search_document_for_signatures/search-document-signatures.txt)
{{< /tab >}}
{{< /tabs >}}

## Example 3: Verify a Signature

Periksa bahwa dokumen memiliki tanda tangan yang Anda harapkan. Verifikasi berhasil ketika tanda tangan teks dengan tepat teks ini ditemukan.

{{< tabs \"verify_text_signature\">}}
{{< tab "Python" >}}
```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```
{{< /tab >}}
{{< tab \"signed.pdf\" >}}

`signed.pdf` adalah file contoh yang digunakan dalam contoh ini. Klik [di sini](https://docs.groupdocs.com/signature/python-net/_sample_files/getting-started/quick-start-guide/signed.pdf) untuk mengunduhnya.

{{< /tab >}}
{{< tab \"verify-text-signature.txt\" >}}
```text
Document is signed by John Smith: True
```
[Download full output](https://docs.groupdocs.com/signature/python-net/_output_files/getting-started/quick-start-guide/verify_text_signature/verify-text-signature.txt)
{{< /tab >}}
{{< /tabs >}}

## Run the Examples

Simpan setiap contoh ke file `.py` masing-masing di samping file contoh. Folder Anda harus terlihat serupa dengan ini:

```Directory
📂 demo-app
 ├──sign_pdf_with_text_signature.py
 ├──search_document_for_signatures.py
 ├──verify_text_signature.py
 ├──sample.pdf
 └──signed.pdf
```

Jalankan contoh dari folder tersebut:

{{< tabs \"run-the-app\">}}
{{< tab "Windows" >}}
```ps
py sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "Linux" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< tab "macOS" >}}
```bash
python3 sign_pdf_with_text_signature.py
```
{{< /tab >}}
{{< /tabs >}}

Setelah selesai, nonaktifkan lingkungan virtual dengan menjalankan `deactivate` atau menutup shell Anda.

## Apply a License

Setel variabel lingkungan `GROUPDOCS_LIC_PATH` ke jalur lengkap file lisensi Anda, dan lisensi akan diterapkan secara otomatis ketika `groupdocs.signature` diimpor. Tidak diperlukan kode. Sebagai alternatif, terapkan dalam kode sekali, sebelum panggilan lainnya:

```python
from groupdocs.signature import License

License().set_license("/path/to/GroupDocs.Signature.lic")
```

Topik [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/) mencakup kedua cara dan lisensi bermeter.

## Next Steps

Setelah menyelesaikan dasar-dasar, jelajahi sumber daya tambahan:
- [Developer Guide](https://docs.groupdocs.com/signature/python-net/developer-guide/): runnable examples for every signature type and operation.
- [Supported File Formats](https://docs.groupdocs.com/signature/python-net/supported-file-formats/): review the full list of supported file types.
- [Licensing](https://docs.groupdocs.com/signature/python-net/licensing/): details on licensing and evaluation.
- [Troubleshooting](https://docs.groupdocs.com/signature/python-net/getting-started/troubleshooting/): solutions to common errors.
- [Technical Support](https://docs.groupdocs.com/signature/python-net/technical-support/): contact support if you run into issues.
