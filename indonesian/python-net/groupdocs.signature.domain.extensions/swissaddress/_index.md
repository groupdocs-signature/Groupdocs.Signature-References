---
title: "Kelas SwissAddress"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan alamat kreditur atau debitur."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/swissaddress/
is_root: false
weight: 330
---


## SwissAddress class

Menunjukkan alamat kreditur atau debitur.

Anda dapat mengatur street, house number, postal code, dan town (tipe alamat terstruktur) atau address line 1 dan 2 (tipe elemen alamat gabungan).

Tipe SwissAddress menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/__init__/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [address_line1](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line1/) | Address line 1, yang berisi street name, house number, atau P.O. box, bersifat opsional dan hanya digunakan untuk alamat dengan elemen gabungan. |
| [address_line2](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/address_line2/) | Address line 2, yang berisi postal code dan town, wajib untuk alamat dengan elemen gabungan. |
| [country_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/country_code/) | Kode negara ISO dua huruf. Kode negara wajib kecuali seluruh alamat berisi nilai null atau kosong. |
| [house_no](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/house_no/) | House number. Field ini hanya digunakan untuk alamat terstruktur dan bersifat opsional. |
| [name](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/name/) | Nama, baik nama depan dan belakang orang alami atau nama perusahaan orang hukum. |
| [postal_code](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/postal_code/) | Postal code. Field ini hanya digunakan untuk alamat terstruktur. Untuk tipe ini, wajib. |
| [street](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/street/) | Street alamat, tanpa house number; bersifat opsional dan hanya digunakan untuk alamat terstruktur. |
| [town](/signature/python-net/groupdocs.signature.domain.extensions/swissaddress/town/) | Town atau city, hanya digunakan untuk alamat terstruktur dan wajib untuk tipe ini. |

### Lihat Juga
* module [`groupdocs.signature.domain.extensions`](/signature/python-net/groupdocs.signature.domain.extensions/)
