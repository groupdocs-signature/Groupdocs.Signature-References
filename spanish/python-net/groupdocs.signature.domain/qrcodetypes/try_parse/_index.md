---
title: "método try_parse"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Devuelve el tipo QRCode que coincide con el nombre de tipo de análisis proporcionado, o None si el nombre es desconocido."
type: docs
url: /es/python-net/groupdocs.signature.domain/qrcodetypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Devuelve el tipo QRCode que coincide con el nombre de tipo de análisis proporcionado, o None si el nombre es desconocido.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parsing_type | `str` | Cadena de origen del nombre de tipo QRCode. |

**Returns:** QrCodeTypes or None: QRCode type instance, or None when the name is not recognized.

### Ver también
* class [`QrCodeTypes`](/signature/python-net/groupdocs.signature.domain/qrcodetypes/)
