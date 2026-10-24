---
title: "método try_parse"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Devuelve un tipo de sello para el nombre del tipo de análisis proporcionado."
type: docs
url: /es/python-net/groupdocs.signature.domain/stamptypes/try_parse/
is_root: false
weight: 1020
---


## try_parse {#parsing_type}

Devuelve un tipo de sello para el nombre del tipo de análisis proporcionado. Si el nombre del sello es desconocido, no se lanza ninguna excepción y el método devuelve None.

```python
def try_parse(cls, parsing_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parsing_type | `str` | Cadena origen del nombre del tipo de sello. |

**Returns:** StampType: StampType instance.

### Ver también
* class [`StampTypes`](/signature/python-net/groupdocs.signature.domain/stamptypes/)
