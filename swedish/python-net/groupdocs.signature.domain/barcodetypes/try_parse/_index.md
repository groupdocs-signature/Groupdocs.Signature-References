---
title: "try_parse metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Returnerar Barcode-typen som matchar det angivna parsningstypnamnet."
type: docs
url: /sv/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Returnerar Barcode-typen som matchar det angivna parsningstypnamnet.

Om namnet är okänt returnerar metoden None istället för att kasta ett undantag.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parsing_type | `str` | Källsträng för streckkodstypens namn. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Se även
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
