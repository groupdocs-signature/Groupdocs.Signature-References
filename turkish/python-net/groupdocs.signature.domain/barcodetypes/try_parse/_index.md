---
title: "try_parse yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Verilen ayrıştırma türü adıyla eşleşen Barcode tipini döndürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Verilen ayrıştırma türü adıyla eşleşen Barcode tipini döndürür.

İsim bilinmiyorsa, yöntem bir istisna yükseltmek yerine None döndürür.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parsing_type | `str` | Barkod türü adının kaynak dizesi. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Ayrıca Bakınız
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
