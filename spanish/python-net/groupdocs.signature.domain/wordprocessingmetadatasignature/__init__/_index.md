---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa un WordProcessingMetadataSignature con el nombre especificado y un valor vacío."
type: docs
url: /es/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inicializa un WordProcessingMetadataSignature con el nombre especificado y un valor vacío.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | WordProcessing Metadata Signature nombre. |

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# Crear firmas de metadatos con nombre y valor
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

Inicializa una firma de metadatos de WordProcessing con valores predefinidos.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

with Signature("sample.docx") as signature:
    options = MetadataSignOptions()
    signatures = [
        WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
        WordProcessingMetadataSignature("DateCreated", datetime.now()),
        WordProcessingMetadataSignature("DocumentId", 123456),
        WordProcessingMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.docx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### Ver también
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
