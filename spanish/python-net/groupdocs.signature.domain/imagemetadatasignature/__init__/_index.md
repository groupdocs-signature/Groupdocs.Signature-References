---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una firma de metadatos de imagen con el identificador y valor especificados."
type: docs
url: /es/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

Inicializa una firma de metadatos de imagen con el identificador y valor especificados.

```python
def __init__(self, id, value):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| id | `System.UInt16` | Identificador único para la firma de metadatos de imagen. Consulte las referencias para las especificaciones de etiquetas EXIF y los posibles valores de id. |
| value | `Any` | El valor de los metadatos. |

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### Ver también
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
