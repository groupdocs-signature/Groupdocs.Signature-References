---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un PresentationMetadataSignature con el nombre especificado y un valor vacío."
type: docs
url: /es/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inicializa un PresentationMetadataSignature con el nombre especificado y un valor vacío.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre de la firma de metadatos de presentación. |

## __init__ {#name-value}

Inicializa un PresentationMetadataSignature con valores predefinidos.

```python
def __init__(self, name, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre del objeto de firma de metadatos. |
| value | `Any` | Valor de la firma de metadatos. |

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Ver también
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
