---
title: "try_parse metodo"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Restituisce il tipo Barcode corrispondente al nome del tipo di parsing fornito."
type: docs
url: /it/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Restituisce il tipo Barcode corrispondente al nome del tipo di parsing fornito.

Se il nome è sconosciuto, il metodo restituisce None invece di sollevare un'eccezione.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parsing_type | `str` | Stringa di origine del nome del tipo di codice a barre. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Vedi anche
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
