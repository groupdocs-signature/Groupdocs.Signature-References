---
title: "Kelas DigitalSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Kelas ini berisi properti tanda tangan digital."
type: docs
url: /id/python-net/groupdocs.signature.domain/digitalsignature/
is_root: false
weight: 150
---


## DigitalSignature class

Kelas ini berisi properti tanda tangan digital.

Tipe DigitalSignature menampilkan anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/) | Menginisialisasi tanda tangan digital dengan parameter default. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#signature_id) | Menginisialisasi tanda tangan digital dengan pengidentifikasi tanda tangan yang diketahui. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store) | Menginisialisasi DigitalSignature menggunakan sertifikat pertama dari penyimpanan X509 yang ditentukan. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#store-index) | Menginisialisasi DigitalSignature berdasarkan penyimpanan X509 dan indeks sertifikat yang ditentukan. |
| [__init__](/signature/python-net/groupdocs.signature.domain/digitalsignature/__init__/#certificate) | Menginisialisasi tanda tangan digital dengan sertifikat yang ditentukan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/digitalsignature/clone/) | Mengkloning instance tanda tangan barcode. |
| [equals](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals/#obj) | Membandingkan tanda tangan ini dengan tanda tangan lain untuk kesamaan. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/digitalsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/digitalsignature/get_hash_code/) | Mengembalikan kode hash untuk tanda tangan digital. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/) | Muat tanda tangan digital dari semua penyimpanan sertifikat X509 sistem. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Muat tanda tangan digital dari penyimpanan sertifikat. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name) | Muat tanda tangan digital dari penyimpanan sertifikat. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Muat tanda tangan digital dari penyimpanan sertifikat digital yang ditempatkan di lokasi tertentu. |
| [load_digital_signatures](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures/#store_name-store_location) | Muat tanda tangan digital dari penyimpanan sertifikat digital yang ditempatkan pada lokasi tertentu. |
| [load_digital_signatures_file](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_file/) |  |
| [load_digital_signatures_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_store_name/) |  |
| [load_digital_signatures_string](/signature/python-net/groupdocs.signature.domain/digitalsignature/load_digital_signatures_string/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [certificate](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate/) | Sertifikat X509 yang terkait dengan tanda tangan digital. |
| [certificate_custom_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_custom_store_name/) | Nama penyimpanan khusus untuk sertifikat. |
| [certificate_store_location](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_location/) | Lokasi penyimpanan sertifikat. |
| [certificate_store_name](/signature/python-net/groupdocs.signature.domain/digitalsignature/certificate_store_name/) | Nama penyimpanan sertifikat. |
| [comments](/signature/python-net/groupdocs.signature.domain/digitalsignature/comments/) | Komentar tujuan penandatanganan. |
| [is_valid](/signature/python-net/groupdocs.signature.domain/digitalsignature/is_valid/) | Tanda tangan digital valid dan dokumen tidak dimanipulasi. |
| [sign_time](/signature/python-net/groupdocs.signature.domain/digitalsignature/sign_time/) | Waktu dokumen ditandatangani. |
| [thumbprint](/signature/python-net/groupdocs.signature.domain/digitalsignature/thumbprint/) | Sidik jari sertifikat. |
| [xad_es_type](/signature/python-net/groupdocs.signature.domain/digitalsignature/xad_es_type/) | Tipe XAdES ([`DigitalSignature.x_ad_es_type`](/signature/python-net/groupdocs.signature.domain/digitalsignature/)). |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Tanggal pembuatan tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bendera yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Tinggi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bendera yang menunjukkan apakah komponen ini mewakili tanda tangan (`True`) atau konten dokumen (`False`). (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Posisi kiri tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Tanggal modifikasi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Nomor halaman tempat tanda tangan ditemukan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Pengidentifikasi unik tanda tangan, digunakan untuk memodifikasi tanda tangan dalam dokumen melalui operasi pembaruan atau penghapusan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Jenis tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Posisi atas tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Lebar tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSearchOptions

def list_digital_signatures():
    with Signature("signed.pdf") as signature:
        result = signature.search([DigitalSearchOptions()])
        for digital in result.signatures:
            print(f"Signed on {digital.sign_time}")
            print(f"Certificate subject: {digital.certificate.subject}")
            print(f"Valid: {digital.is_valid}")

if __name__ == "__main__":
    list_digital_signatures()
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
