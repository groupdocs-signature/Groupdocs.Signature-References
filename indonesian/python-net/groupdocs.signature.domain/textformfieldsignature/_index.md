---
title: "Kelas TextFormFieldSignature"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili properti tanda tangan bidang formulir input teks untuk dokumen PDF."
type: docs
url: /id/python-net/groupdocs.signature.domain/textformfieldsignature/
is_root: false
weight: 730
---


## TextFormFieldSignature class

Mewakili properti tanda tangan bidang formulir input teks untuk dokumen PDF.

Tipe TextFormFieldSignature menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name) | Menginisialisasi PdfTextFormFieldSignature dengan nama yang telah ditentukan. |
| [__init__](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/#name-text) | Menginisialisasi PdfTextFormFieldSignature dengan nama yang telah ditentukan. |

### Metode
| Metode | Deskripsi |
| :- | :- |
| [clone](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/clone/) | Kloning instance FormField Signature. |
| [equals](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals/#obj) | Membandingkan tanda tangan ini dengan tanda tangan lain untuk kesetaraan berdasarkan tipe dan nilai properti. |
| [equals_object](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/equals_object/) |  |
| [get_hash_code](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/get_hash_code/) | Menimpa metode GetHashCode. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [text](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/text/) | Teks input bidang formulir. |
| [created_on](/signature/python-net/groupdocs.signature.domain/basesignature/created_on/) | Tanggal pembuatan tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [deleted](/signature/python-net/groupdocs.signature.domain/basesignature/deleted/) | Bendera yang menunjukkan apakah tanda tangan ini telah dihapus dari dokumen. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [height](/signature/python-net/groupdocs.signature.domain/basesignature/height/) | Tinggi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [is_signature](/signature/python-net/groupdocs.signature.domain/basesignature/is_signature/) | Bendera yang menunjukkan apakah komponen ini mewakili tanda tangan (`True`) atau konten dokumen (`False`). (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [left](/signature/python-net/groupdocs.signature.domain/basesignature/left/) | Posisi kiri tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [modified_on](/signature/python-net/groupdocs.signature.domain/basesignature/modified_on/) | Tanggal modifikasi tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [name](/signature/python-net/groupdocs.signature.domain/formfieldsignature/name/) | Nama bidang formulir yang unik. (diturunkan dari [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [page_number](/signature/python-net/groupdocs.signature.domain/basesignature/page_number/) | Nomor halaman tempat tanda tangan ditemukan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_id](/signature/python-net/groupdocs.signature.domain/basesignature/signature_id/) | Pengidentifikasi unik tanda tangan, digunakan untuk memodifikasi tanda tangan dalam dokumen melalui operasi pembaruan atau penghapusan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [signature_type](/signature/python-net/groupdocs.signature.domain/basesignature/signature_type/) | Jenis tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [top](/signature/python-net/groupdocs.signature.domain/basesignature/top/) | Posisi atas tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |
| [type](/signature/python-net/groupdocs.signature.domain/formfieldsignature/type/) | Tipe bidang formulir. (diturunkan dari [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [value](/signature/python-net/groupdocs.signature.domain/formfieldsignature/value/) | Objek data bidang formulir. (diturunkan dari [`FormFieldSignature`](/signature/python-net/groupdocs.signature.domain/formfieldsignature/)) |
| [width](/signature/python-net/groupdocs.signature.domain/basesignature/width/) | Lebar tanda tangan. (diturunkan dari [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature


def sign_with_form_field_signature():
    with Signature("sample.pdf") as signature:
        # Buat bidang formulir teks bernama "FieldText" dengan nilai "Value1"
        text_field = TextFormFieldSignature("FieldText", "Value1")

        # Buat opsi bidang formulir untuk itu
        options = FormFieldSignOptions(text_field)

        # Atur posisi dan ukuran bidang formulir
        options.left = 100
        options.top = 400
        options.width = 200
        options.height = 20

        # Tandatangani dokumen dan simpan hasilnya
        result = signature.sign("signed_form_field.pdf", options)
        for field in result.succeeded:
            print(f"Added form field '{field.name}' with value '{field.value}'")
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
