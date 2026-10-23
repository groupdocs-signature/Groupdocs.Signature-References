---
title: "Kelas MetadataSearchOptions"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili opsi pencarian untuk tanda tangan Metadata."
type: docs
url: /id/python-net/groupdocs.signature.options/metadatasearchoptions/
is_root: false
weight: 310
---


## MetadataSearchOptions class

Mewakili opsi pencarian untuk tanda tangan Metadata.

Menyediakan opsi untuk mengonfigurasi pencarian tanda tangan metadata dalam dokumen.

- Basic usage of search for Metadata electronic signature by GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+Metadata+e-signatures
- Advanced usage of settings of search for Metadata electronic signature with GroupDocs.Signature: https://docs.groupdocs.com/display/signaturenet/Search+for+built-in+Metadata+signatures

Tipe MetadataSearchOptions menampilkan anggota-anggota berikut:

### Konstruktor
| Konstruktor | Deskripsi |
| :- | :- |
| [__init__](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/) | Menginisialisasi instance baru dari kelas MetadataSearchOptions dengan nilai default. |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [data_encryption](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/data_encryption/) | Implementasi dari [`IDataEncryption`](/signature/python-net/groupdocs.signature.domain.extensions/idataencryption/) yang digunakan untuk mendekripsi semua tanda tangan metadata dalam koleksi opsi ini. |
| [include_builtin_properties](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/include_builtin_properties/) | Bendera yang menunjukkan apakah properti dokumen bawaan seperti statistik dokumen dan informasi termasuk dalam hasil pencarian. |
| [name](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name/) | Nama tanda tangan metadata yang akan dicari dan dicocokkan. |
| [name_match_type](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/name_match_type/) | Tipe pencocokan nama metadata yang digunakan untuk pencarian. Ini diterapkan hanya ketika properti `name` diatur. |
| [all_pages](/signature/python-net/groupdocs.signature.options/searchoptions/all_pages/) | Bendera yang menunjukkan apakah akan mencari pada setiap halaman dokumen. Secara default nilai ini adalah True. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [page_number](/signature/python-net/groupdocs.signature.options/searchoptions/page_number/) | Nomor halaman dokumen untuk pencarian (opsional). (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [pages_setup](/signature/python-net/groupdocs.signature.options/searchoptions/pages_setup/) | Opsi untuk menentukan halaman untuk pencarian tanda tangan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [shape_position](/signature/python-net/groupdocs.signature.options/searchoptions/shape_position/) | Bendera yang menunjukkan apakah mengembalikan posisi bentuk dalam tata letak dokumen. Hanya tersedia untuk dokumen Word. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |
| [skip_external](/signature/python-net/groupdocs.signature.options/searchoptions/skip_external/) | Bendera untuk mengembalikan hanya tanda tangan yang ditandai sebagai `IsSignature`. Secara default nilai adalah `False`, yang menunjukkan bahwa semua tanda tangan yang cocok dengan kriteria yang ditentukan dikembalikan. (diturunkan dari [`SearchOptions`](/signature/python-net/groupdocs.signature.options/searchoptions/)) |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.domain import TextMatchType
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    options = MetadataSearchOptions()
    options.name = "Author"
    options.name_match_type = TextMatchType.EXACT

    result = signature.search([options])
    print(f"Found {len(result.signatures)} matching metadata signature(s)")
    for metadata in result.signatures:
        print(f"{metadata.name} = {metadata.value}")
```

### Lihat Juga
* module [`groupdocs.signature.options`](/signature/python-net/groupdocs.signature.options/)
