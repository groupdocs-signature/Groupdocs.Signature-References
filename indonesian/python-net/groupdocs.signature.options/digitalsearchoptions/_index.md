---
title: "Kelas DigitalSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi pencarian untuk tanda tangan Digital."
type: docs
url: /id/python-net/groupdocs.signature.options/digitalsearchoptions/
is_root: false
weight: 130
---


## DigitalSearchOptions class

Menunjukkan opsi pencarian untuk tanda tangan Digital.

Pelajari lebih lanjut

- Basic usage of search for Digital electronic signature by GroupDocs.Signature: How to eSearch Digital signatures in a document (https://docs.groupdocs.com/display/signaturenet/Search+for+Digital+e-signatures)
- Advanced usage of settings of search for Digital electronic signature with GroupDocs.Signature: Advanced usage of eSearch Digital signatures in a document and additional settings (https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Digital+signatures)

Tipe DigitalSearchOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/__init__/) | Menginisialisasi instance baru dari kelas DigitalSearchOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [comments](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/comments/) | Komentar tanda tangan digital yang akan dicari. |
| [issuer_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/issuer_name/) | Nama terdistinguish dari penerbit sertifikat yang akan dicari ketika nilai tidak kosong. |
| [sign_date_time_from](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_from/) | Rentang tanggal dan waktu tanda tangan Digital yang akan dicari. Nilai yang dapat null akan diabaikan. |
| [sign_date_time_to](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/sign_date_time_to/) | Akhir rentang tanggal dan waktu tanda tangan digital yang akan dicari. Nilai null akan diabaikan. |
| [subject_name](/signature/python-net/groupdocs.signature.options/digitalsearchoptions/subject_name/) | Nama subjek terdistinguish dari sertifikat yang akan dicari ketika nilai tidak kosong diberikan. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Bendera yang menunjukkan apakah akan mencari pada setiap halaman dokumen. Secara default nilai ini adalah True. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Nomor halaman dokumen untuk pencarian (opsional). (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Opsi untuk menentukan halaman untuk pencarian tanda tangan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Bendera yang menunjukkan apakah mengembalikan posisi bentuk dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Bendera untuk mengembalikan hanya tanda tangan yang ditandai sebagai `IsSignature`. Secara default nilai adalah `False`, yang menunjukkan bahwa semua tanda tangan yang cocok dengan kriteria yang ditentukan dikembalikan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
