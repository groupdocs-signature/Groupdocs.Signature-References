---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un objeto BarcodeSignature con un identificador de firma obtenido después de un proceso de búsqueda."
type: docs
url: /es/python-net/groupdocs.signature.domain/barcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Inicializa un objeto BarcodeSignature con un identificador de firma obtenido después de un proceso de búsqueda. El identificador se utiliza para recuperar propiedades adicionales de esta firma desde la capa de información de firmas del documento.

```python
def __init__(self, signature_id):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_id | `str` | Identificador de firma único obtenido mediante el método `Sign` o `Search` de `Signature`. |

### Ver también
* class [`BarcodeSignature`](/signature/python-net/groupdocs.signature.domain/barcodesignature/)
