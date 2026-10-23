---
title: "Kelas Mailmark2D"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menyandi dan mendekode teks yang tertanam dalam Royal Mail 2D Mailmark."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/mailmark2d/
is_root: false
weight: 220
---


## Mailmark2D class

Menyandi dan mendekode teks yang tertanam dalam Royal Mail 2D Mailmark.

Tipe Mailmark2D menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/__init__/) | Menginisialisasi data gabungan Royal Mail Mailmark dengan nilai data utama dan sekunder default. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/clone/) | Mengembalikan salinan objek ini. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [class_](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/class_/) | Kelas dari item. |
| [customer_content](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content/) | Ruang opsional untuk penggunaan oleh pelanggan. |
| [customer_content_encode_mode](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/customer_content_encode_mode/) | Mode enkode barcode DataMatrix. Nilai default: `DataMatrixEncodeMode.c40`. |
| [data_matrix_type](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/data_matrix_type/) | Tipe Mailmark 2D menentukan ukuran barcode Data Matrix. |
| [destination_post_code_and_dps](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/destination_post_code_and_dps/) | Properti ini menyimpan kode pos alamat pengiriman dengan DPS, yang untuk alamat daratan terdiri dari area (1‑2 karakter), distrik (1‑2 karakter), sektor (1 karakter), unit (2 karakter), dan DPS (2 karakter), harus mengikuti format PAF® yang valid, dan memiliki panjang maksimum 9 karakter. |
| [information_type_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/information_type_id/) | Pengidentifikasi payload barcode Royal Mail Mailmark untuk setiap tipe produk. |
| [item_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/item_id/) | Pengidentifikasi unik item dalam Supply Chain ID, diperlukan pada setiap barcode Mailmark untuk identifikasi unik setidaknya selama 90 hari (nilai maksimum: 99999999). |
| [return_to_sender_post_code](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/return_to_sender_post_code/) | Kode Pos Pengembalian ke Pengirim tanpa DPS. |
| [rts_flag](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/rts_flag/) | Bendera yang menunjukkan tingkat layanan Pengembalian ke Pengirim yang diminta. Panjang maksimum adalah 1. |
| [supply_chain_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/supply_chain_id/) | Grup unik pelanggan yang terlibat dalam pengiriman surat. |
| [upu_country_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/upu_country_id/) | ID Negara UPU (panjang maksimum: 4 karakter). |
| [version_id](/signature/python-net/groupdocs.signature.domain.extensions/mailmark2d/version_id/) | Pengidentifikasi versi barcode yang relevan untuk setiap ID Tipe Informasi. |

### Lihat Juga
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
