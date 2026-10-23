---
title: "Kelas SignatureSettings"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili pengaturan untuk menyesuaikan perilaku Signature."
type: docs
url: /id/python-net/groupdocs.signature/signaturesettings/
is_root: false
weight: 140
---


## SignatureSettings class

Mewakili pengaturan untuk menyesuaikan perilaku [`Signature`](/signature/python-net/groupdocs.signature/signature/).

Tipe SignatureSettings mengekspos anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/) | Menginisialisasi instance SignatureSettings default dengan nilai-nilai default. |
| [__init__](/signature/python-net/groupdocs.signature/signaturesettings/__init__/#logger) | Menginisialisasi instance SignatureSettings default dengan implementasi Logger. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [default_culture](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) | Budaya default yang digunakan selama pemrosesan dokumen. Nilai defaultnya adalah "en-US". |
| [include_standard_metadata_signatures](/signature/python-net/groupdocs.signature/signaturesettings/include_standard_metadata_signatures/) | Flag yang menunjukkan apakah tanda tangan metadata dokumen standar seperti Penulis, Pemilik, tanggal pembuatan, dan tanggal modifikasi termasuk dalam daftar metadata. |
| [log_level](/signature/python-net/groupdocs.signature/signaturesettings/log_level/) | Flag level log yang menentukan jenis pesan apa yang diteruskan ke [`SignatureSettings.Logger`](/signature/python-net/groupdocs.signature/signaturesettings/logger/). |
| [logger](/signature/python-net/groupdocs.signature/signaturesettings/logger/) | Implementasi logger yang digunakan untuk pencatatan (Error, Warning, Trace). [`ILogger`](/signature/python-net/groupdocs.signature.logging/ilogger/). |
| [save_document_on_empty_delete](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_delete/) | Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode Delete tidak memiliki tanda tangan yang terpengaruh untuk dihapus. |
| [save_document_on_empty_update](/signature/python-net/groupdocs.signature/signaturesettings/save_document_on_empty_update/) | Flag yang menentukan apakah dokumen sumber disimpan kembali ketika metode `Update` tidak memiliki tanda tangan untuk diperbarui. |
| [show_deleted_signatures_info](/signature/python-net/groupdocs.signature/signaturesettings/show_deleted_signatures_info/) | Flag yang menentukan apakah tanda tangan yang dihapus termasuk dalam hasil informasi dokumen. Setiap [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) memiliki flag `Deleted` untuk menunjukkan apakah telah dihapus. |

### Lihat Juga
* module [`groupdocs.signature`](/signature/python-net/groupdocs.signature/)
