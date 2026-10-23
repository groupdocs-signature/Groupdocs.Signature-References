---
title: "Kelas Signature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili kelas utama yang mengontrol proses penandatanganan dokumen."
type: docs
url: /id/python-net/groupdocs.signature/signature/
is_root: false
weight: 130
---


## Signature class

Mewakili kelas utama yang mengontrol proses penandatanganan dokumen.

Pelajari lebih lanjut tentang fitur GroupDocs.Signature:
- https://docs.groupdocs.com/display/signaturenet/Developer+Guide

Tipe Signature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document) | Menginisialisasi instance Signature baru dengan dokumen yang disediakan sebagai aliran. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options) | Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan aliran dokumen dan opsi pemuatan. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-settings) | Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan dokumen yang disediakan melalui aliran dan opsional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#document-load_options-settings) | Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan aliran dokumen, opsi pemuatan, dan pengaturan tanda tangan. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path) | Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan dokumen yang disediakan melalui jalur file. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options) | Menginisialisasi instance Signature baru dengan dokumen yang disediakan melalui jalur file dan opsi pemuatan. |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-settings) | Menginisialisasi instance [`Signature`](/signature/python-net/groupdocs.signature/signature/) baru dengan dokumen yang disediakan melalui jalur file dan opsional [`SignatureSettings`](/signature/python-net/groupdocs.signature/signaturesettings/). |
| [__init__](/signature/python-net/groupdocs.signature/signature/__init__/#file_path-load_options-settings) | Menginisialisasi instance baru dari [`Signature`](/signature/python-net/groupdocs.signature/signature/) dengan dokumen yang disediakan melalui jalur file, opsi pemuatan, dan pengaturan tanda tangan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature) | Menghapus [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) yang ditentukan dari dokumen. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signatures) | Menghapus daftar tanda tangan yang disediakan dari dokumen. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_type) | Menghapus tanda tangan dengan tipe yang ditentukan dari dokumen. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_types) | Menghapus tanda tangan dari daftar `SignatureType` yang ditentukan dari dokumen. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_id) | Menghapus sebuah tanda tangan berdasarkan Id tanda tangan spesifiknya dari dokumen. |
| [delete](/signature/python-net/groupdocs.signature/signature/delete/#signature_ids) | Menghapus tanda tangan yang ditentukan dari dokumen. |
| [delete_base_signature](/signature/python-net/groupdocs.signature/signature/delete_base_signature/) |  |
| [delete_file](/signature/python-net/groupdocs.signature/signature/delete_file/) |  |
| [delete_files](/signature/python-net/groupdocs.signature/signature/delete_files/) |  |
| [delete_list](/signature/python-net/groupdocs.signature/signature/delete_list/) |  |
| [delete_signature_type](/signature/python-net/groupdocs.signature/signature/delete_signature_type/) |  |
| [delete_string](/signature/python-net/groupdocs.signature/signature/delete_string/) |  |
| [delete_strings](/signature/python-net/groupdocs.signature/signature/delete_strings/) |  |
| [dispose](/signature/python-net/groupdocs.signature/signature/dispose/) | Membersihkan sumber daya internal yang digunakan oleh objek tanda tangan. |
| [generate_preview](/signature/python-net/groupdocs.signature/signature/generate_preview/#preview_options) | Membuat pratinjau halaman dokumen. |
| [generate_preview_preview_options](/signature/python-net/groupdocs.signature/signature/generate_preview_preview_options/) |  |
| [generate_signature_preview](/signature/python-net/groupdocs.signature/signature/generate_signature_preview/#preview_options) | Membuat pratinjau tanda tangan berdasarkan SignOptions yang diberikan. |
| [get_document_info](/signature/python-net/groupdocs.signature/signature/get_document_info/) | Mendapatkan informasi tentang halaman dokumen: ukuran mereka, tinggi maksimum halaman, lebar halaman dengan tinggi maksimum. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list) | Mencari tanda tangan dalam dokumen menggunakan daftar [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/). |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options_list-predicate) | Mencari tanda tangan dalam dokumen menggunakan opsi pencarian yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#search_options) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_type) |  |
| [search](/signature/python-net/groupdocs.signature/signature/search/#signature_types) | Mencari tipe tanda tangan yang ditentukan dalam dokumen berdasarkan nilai `SignatureType`. |
| [search](/signature/python-net/groupdocs.signature/signature/search/#predicate) | Mencari tanda tangan dalam dokumen menggunakan semua opsi pencarian yang tersedia dan menyaring hasil berdasarkan predikat yang ditentukan. |
| [search_func](/signature/python-net/groupdocs.signature/signature/search_func/) |  |
| [search_list](/signature/python-net/groupdocs.signature/signature/search_list/) |  |
| [search_search_options](/signature/python-net/groupdocs.signature/signature/search_search_options/) |  |
| [search_signature_type](/signature/python-net/groupdocs.signature/signature/search_signature_type/) |  |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options) | Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options-save_options) | Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list) | Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#document-sign_options_list-save_options) | Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke aliran menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options) | Menandatangani dokumen dengan SignOptions dan menyimpan hasil ke jalur file yang ditentukan. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options-save_options) | Menandatangani dokumen dengan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list) | Menandatangani dokumen dengan koleksi [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan. |
| [sign](/signature/python-net/groupdocs.signature/signature/sign/#file_path-sign_options_list-save_options) | Menandatangani dokumen dengan kumpulan [`SignOptions`](/signature/python-net/groupdocs.signature.options/signoptions/) dan menyimpan hasil ke jalur file yang ditentukan menggunakan [`SaveOptions`](/signature/python-net/groupdocs.signature.options/saveoptions/) yang telah ditentukan sebelumnya. |
| [sign_file](/signature/python-net/groupdocs.signature/signature/sign_file/) |  |
| [sign_stream](/signature/python-net/groupdocs.signature/signature/sign_stream/) |  |
| [sign_streams](/signature/python-net/groupdocs.signature/signature/sign_streams/) |  |
| [sign_string](/signature/python-net/groupdocs.signature/signature/sign_string/) |  |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signature) | Memperbarui BaseSignature tanda tangan yang diberikan dalam dokumen. |
| [update](/signature/python-net/groupdocs.signature/signature/update/#signatures) | Memperbarui tanda tangan yang diberikan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) dalam dokumen. |
| [update_base_signature](/signature/python-net/groupdocs.signature/signature/update_base_signature/) |  |
| [update_list](/signature/python-net/groupdocs.signature/signature/update_list/) |  |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options) | Memverifikasi tanda tangan dokumen dengan data VerifyOptions yang diberikan. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options-predicate) | Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil berdasarkan predikat yang ditentukan. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list) | Memverifikasi tanda tangan dokumen dengan daftar data VerifyOptions. |
| [verify](/signature/python-net/groupdocs.signature/signature/verify/#verify_options_list-predicate) | Memverifikasi tanda tangan dokumen menggunakan opsi verifikasi yang disediakan dan menyaring hasil dengan predikat yang diberikan. |
| [verify_list](/signature/python-net/groupdocs.signature/signature/verify_list/) |  |
| [verify_verify_options](/signature/python-net/groupdocs.signature/signature/verify_verify_options/) |  |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSignOptions

def sign_pdf():
    with Signature("sample.pdf") as signature:
        options = TextSignOptions("John Smith")
        options.left = 100
        options.top = 100
        result = signature.sign("signed_sample.pdf", options)
        print(f"Signatures added: {len(result.succeeded)}")
```

### Guides
Panduan tugas yang menggunakan `Signature`:

* [Quick Start Guide](/signature/python-net/guides/quick-start-guide/)
* [eSign Document with Text Signature](/signature/python-net/guides/esign-document-with-text-signature/)
* [eSign Document with Image Signature](/signature/python-net/guides/esign-document-with-image-signature/)
* [eSign Document with Barcode Signature](/signature/python-net/guides/esign-document-with-barcode-signature/)
* [eSign Document with QR Code Signature](/signature/python-net/guides/esign-document-with-qr-code-signature/)
* [Sign Document with Digital Signature](/signature/python-net/guides/esign-document-with-digital-signature/)
* [eSign Document with Multiple Signatures](/signature/python-net/guides/esign-document-with-multiple-signatures/)
* [Search for Text e-Signatures](/signature/python-net/guides/search-for-text-e-signatures/)
* [Search for Barcode e-Signatures](/signature/python-net/guides/search-for-barcode-e-signatures/)
* [Delete signatures of the certain type](/signature/python-net/guides/delete-signatures-of-the-certain-type/)
* [Generate signatures preview](/signature/python-net/guides/generate-signatures-preview/)
* [Generate document pages preview](/signature/python-net/guides/generate-document-pages-preview/)

### Lihat Juga
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
