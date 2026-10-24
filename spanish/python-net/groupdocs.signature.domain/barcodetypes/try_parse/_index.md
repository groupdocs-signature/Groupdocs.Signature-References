---
title: "método try_parse"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Devuelve el tipo Barcode que coincide con el nombre de tipo de análisis proporcionado."
type: docs
url: /es/python-net/groupdocs.signature.domain/barcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Devuelve el tipo Barcode que coincide con el nombre de tipo de análisis proporcionado.

Si el nombre es desconocido, el método devuelve None en lugar de lanzar una excepción.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parsing_type | `str` | Cadena de origen del nombre del tipo de código de barras. |

**Returns:** BarcodeType: The matching BarcodeType instance, or None if not found.

### Ver también
* class [`BarcodeTypes`](/signature/python-net/groupdocs.signature.domain/barcodetypes/)
