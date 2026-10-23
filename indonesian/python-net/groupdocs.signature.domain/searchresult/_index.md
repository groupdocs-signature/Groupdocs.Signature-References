---
title: "Kelas SearchResult"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mewakili hasil pencarian tanda tangan dalam dokumen yang ditentukan."
type: docs
url: /id/python-net/groupdocs.signature.domain/searchresult/
is_root: false
weight: 590
---


## SearchResult class

Mewakili hasil pencarian tanda tangan dalam dokumen yang ditentukan.

Tipe SearchResult menampilkan anggota-anggota berikut:

### Metode
| Metode | Deskripsi |
| :- | :- |
| [get_enumerator](/signature/python-net/groupdocs.signature.domain/searchresult/get_enumerator/) | Mengembalikan iterator atas hasil pencarian. |
| [to_list](/signature/python-net/groupdocs.signature.domain/searchresult/to_list/) |  |

### Properti
| Properti | Deskripsi |
| :- | :- |
| [destin_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/destin_document_size/) | Ukuran dokumen tujuan, yang selalu 0 untuk metode Search. |
| [failed](/signature/python-net/groupdocs.signature.domain/searchresult/failed/) | Daftar tanda tangan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/) yang gagal dalam proses pencarian berdasarkan kriteria pencarian. |
| [processing_time](/signature/python-net/groupdocs.signature.domain/searchresult/processing_time/) | Waktu eksekusi proses pencarian dalam milidetik. |
| [signatures](/signature/python-net/groupdocs.signature.domain/searchresult/signatures/) | Daftar tanda tangan yang ditemukan [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/). |
| [source_document_size](/signature/python-net/groupdocs.signature.domain/searchresult/source_document_size/) | Ukuran dokumen sumber. |
| [succeeded](/signature/python-net/groupdocs.signature.domain/searchresult/succeeded/) | Daftar tanda tangan yang ditemukan ([`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)). |
| [total_signatures](/signature/python-net/groupdocs.signature.domain/searchresult/total_signatures/) | Jumlah total tanda tangan yang diproses yang dikembalikan oleh proses pencarian. |

### Contoh

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([FormFieldSearchOptions()])
    print(f"Found {len(result.signatures)} form field signature(s)")
```

### Lihat Juga
* module [`groupdocs.signature.domain`](/signature/python-net/groupdocs.signature.domain/)
