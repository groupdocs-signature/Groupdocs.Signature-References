---
title: "metode try_parse"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengembalikan tipe Barcode yang cocok dengan nama tipe parsing yang diberikan."
type: docs
url: /id/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Mengembalikan tipe Barcode yang cocok dengan nama tipe parsing yang diberikan.

Jika nama tidak diketahui, metode mengembalikan None alih-alih melempar pengecualian.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parsing_type | `str` | String sumber dari nama tipe barcode. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Lihat Juga
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
