---
title: "Kelas FormFieldSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menunjukkan opsi pencarian untuk tanda tangan bidang Formulir."
type: docs
url: /id/python-net/groupdocs.signature.options/formfieldsearchoptions/
is_root: false
weight: 170
---


## FormFieldSearchOptions class

Menunjukkan opsi pencarian untuk tanda tangan bidang Formulir.

Pelajari lebih lanjut:
- Basic usage of search for FormField electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures
- Advanced usage of settings of search for FormField electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures

Tipe FormFieldSearchOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/__init__/) | Menginisialisasi instance baru dari kelas FormFieldSearchOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [name](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/name/) | Pola ekspresi reguler yang digunakan untuk mencocokkan nama tanda tangan bidang formulir selama pencarian. |
| [type](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/type/) | Jenis tanda tangan bidang formulir yang akan dicari. Nilai default adalah None. |
| [value](/signature/python-net/groupdocs.signature.options/formfieldsearchoptions/value/) | Nilai tanda tangan bidang formulir yang akan dicari. Default adalah None. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Bendera yang menunjukkan apakah akan mencari pada setiap halaman dokumen. Secara default nilai ini adalah True. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Nomor halaman dokumen untuk pencarian (opsional). (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Opsi untuk menentukan halaman untuk pencarian tanda tangan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Bendera yang menunjukkan apakah mengembalikan posisi bentuk dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Bendera untuk mengembalikan hanya tanda tangan yang ditandai sebagai `IsSignature`. Secara default nilai adalah `False`, yang menunjukkan bahwa semua tanda tangan yang cocok dengan kriteria yang ditentukan dikembalikan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import FormFieldType
from groupdocs.signature.options import FormFieldSearchOptions


def search_form_fields_by_name():
    with Signature("signed.pdf") as signature:
        options = FormFieldSearchOptions()
        # Kembalikan hanya bidang teks yang bernama "ApprovedBy"
        options.type = FormFieldType.TEXT
        options.name = "ApprovedBy"

        result = signature.search([options])

        print(f"Found {len(result.signatures)} matching form field signature(s)")
        for field in result.signatures:
            print(f"Field '{field.name}' on page {field.page_number}, value: {field.value}")


if __name__ == "__main__":
    search_form_fields_by_name()
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
