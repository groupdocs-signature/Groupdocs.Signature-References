---
title: "try_parse methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Retourneert het Barcode‑type dat overeenkomt met de opgegeven parsingsnaam."
type: docs
url: /nl/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Retourneert het Barcode‑type dat overeenkomt met de opgegeven parsingsnaam.

Als de naam onbekend is, retourneert de methode None in plaats van een uitzondering te genereren.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parsing_type | `str` | Bronstring van de barcode-typenaam. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Zie ook
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
