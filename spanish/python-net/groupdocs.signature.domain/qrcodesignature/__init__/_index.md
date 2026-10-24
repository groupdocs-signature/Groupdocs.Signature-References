---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un objeto QrCodeSignature con un identificador de firma obtenido después de un proceso de búsqueda."
type: docs
url: /es/python-net/groupdocs.signature.domain/qrcodesignature/__init__/
is_root: false
weight: 10
---


## __init__ {#signature_id}

Inicializa un objeto QrCodeSignature con un identificador de firma obtenido después de un proceso de búsqueda.

El identificador único se utiliza para recuperar propiedades adicionales de esta firma desde la capa de información de firmas del documento.

```python
def __init__(self, signature_id):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| signature_id | `str` | Identificador único de la firma obtenido mediante el método sign o search. |

### Ver también
* class [`QrCodeSignature`](/signature/python-net/groupdocs.signature.domain/qrcodesignature/)
