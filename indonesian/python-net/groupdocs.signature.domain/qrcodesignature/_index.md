---
title: "Kelas QrCodeSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili properti tanda tangan QR-code."
type: docs
url: /id/python-net/groupdocs.signature.domain/qrcodesignature/
is_root: false
weight: 550
---


## QrCodeSignature class

Mewakili properti tanda tangan QR-code.

Tipe QrCodeSignature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/qrcodesignature/__init__/#signature_id) | Menginisialisasi objek QrCodeSignature dengan pengidentifikasi tanda tangan yang diperoleh setelah proses pencarian. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/qrcodesignature/clone/) | Mengkloning instance Tanda Tangan QR-Code. |
| [equals](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals/#obj) | Menentukan apakah objek tanda tangan yang diberikan sama dengan instance ini. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/qrcodesignature/equals_object/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/) |  |
| [get_data](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data/#data_encryption) |  |
| [get_data_idata_encryption](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_data_idata_encryption/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/qrcodesignature/get_hash_code/) | Menimpa metode GetHashCode. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [content](/signature/python-net/groupdocs.signature.domain/qrcodesignature/content/) | Konten gambar data biner QR-code dengan tipe [`QrCodeSignature.format`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/). |
| [encode_type](/signature/python-net/groupdocs.signature.domain/qrcodesignature/encode_type/) | Tipe enkode QR-code. |
| [format](/signature/python-net/groupdocs.signature.domain/qrcodesignature/format/) | Format gambar tanda tangan QR-code. |
| [text](/signature/python-net/groupdocs.signature.domain/qrcodesignature/text/) | Teks QR-code. |
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
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([QrCodeSearchOptions()])
    if result.signatures:
        qr = result.signatures[0]
        print(qr.text, qr.encode_type.type_name, qr.left, qr.top)
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
