---
title: "méthode try_parse"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Renvoie le type Barcode correspondant au nom de type d'analyse donné."
type: docs
url: /fr/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Renvoie le type Barcode correspondant au nom de type d'analyse donné.

Si le nom est inconnu, la méthode renvoie None au lieu de lever une exception.

```python
def try_parse(cls, parsing_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| parsing_type | `str` | Chaîne source du nom du type de code-barres. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Voir aussi
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
