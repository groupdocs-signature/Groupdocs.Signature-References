---
title: "kelas QrCodeSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi pencarian untuk tanda tangan QR-Code."
type: docs
url: /id/python-net/groupdocs.signature.options/qrcodesearchoptions/
is_root: false
weight: 470
---


## QrCodeSearchOptions class

Mewakili opsi pencarian untuk tanda tangan QR-Code.

- Basic usage of search for QR-Code electronic signature by GroupDocs.Signature: How to eSearch QR-Code signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+QR-Code+e-signatures)
- Advanced usage of settings of search for QR-Code electronic signature with GroupDocs.Signature: Advanced usage of eSearch QR-Code signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+QR-code+signatures)

Tipe QrCodeSearchOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/) | Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan nilai default. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type) | Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan nilai tipe enkode. |
| [__init__](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/#encode_type-text) | Menginisialisasi sebuah instance baru dari kelas QRCodeSearchOptions dengan tipe enkode dan nilai teks. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/data_encryption/) | Implementasi dari [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) yang digunakan untuk mengkodekan dan mendekode teks tanda tangan QR-Code atau properti data. |
| [encode_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/encode_type/) | Tipe enkode untuk mencari kode QR. |
| [match_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/match_type/) | Tipe pencocokan teks QR-Code yang digunakan selama pencarian. |
| [return_content](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content/) | Flag yang menentukan apakah konten gambar QR‑Code dikembalikan untuk setiap tanda tangan pada halaman dokumen. Ketika diatur ke True, data gambar mentah disimpan dalam properti `content` tanda tangan menggunakan format yang ditentukan oleh `return_content_type`. Dinonaktifkan secara default. |
| [return_content_type](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/return_content_type/) | Tipe file dari konten gambar yang dikembalikan dari tanda tangan QR-Code ketika properti `return_content` diaktifkan. |
| [text](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/text/) | Teks tanda tangan QR-Code yang akan dicari dan dicocokkan. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Bendera yang menunjukkan apakah akan mencari pada setiap halaman dokumen. Secara default nilai ini adalah True. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Nomor halaman dokumen untuk pencarian (opsional). (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Opsi untuk menentukan halaman untuk pencarian tanda tangan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Bendera yang menunjukkan apakah mengembalikan posisi bentuk dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Bendera untuk mengembalikan hanya tanda tangan yang ditandai sebagai `IsSignature`. Secara default nilai adalah `False`, yang menunjukkan bahwa semua tanda tangan yang cocok dengan kriteria yang ditentukan dikembalikan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    print(f"Found {len(result.signatures)} QR code signature(s)")
    for qr in result.signatures:
        print(f"QR code signature found at page {qr.page_number} with type {qr.encode_type.type_name} and text '{qr.text}'")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
