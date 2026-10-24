---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una firma de metadatos PDF con un nombre predefinido y un valor vacío."
type: docs
url: /es/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inicializa una firma de metadatos PDF con un nombre predefinido y un valor vacío.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre de la firma de metadatos PDF. |

## __init__ {#name-value}

Inicializa una firma de metadatos PDF con valores predefinidos.

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
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

Inicializa una firma de metadatos PDF con valores predefinidos.

```python
def __init__(self, name, value, tag):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre del objeto de firma de metadatos. |
| value | `Any` | Valor de la firma de metadatos. |
| tag | `str` | Etiqueta de prefijo de la firma de metadatos. |

### Ejemplo

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Crear una firma de metadatos para el autor del PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Crear una firma de metadatos para la fecha de creación
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Crear una firma de metadatos para un identificador numérico
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Crear una firma de metadatos para un valor de punto flotante
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Ver también
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
