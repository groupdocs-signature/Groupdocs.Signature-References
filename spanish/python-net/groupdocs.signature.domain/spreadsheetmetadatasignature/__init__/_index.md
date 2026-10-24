---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa Spreadsheet Metadata Signature con un nombre predefinido y valor vacío."
type: docs
url: /es/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inicializa Spreadsheet Metadata Signature con un nombre predefinido y valor vacío.

```python
def __init__(self, name):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| name | `str` | Nombre de la firma de metadatos de hoja de cálculo. |

## __init__ {#name-value}

Inicializa una Spreadsheet Metadata Signature con valores predefinidos.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Crear firmas de metadatos para una hoja de cálculo
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Ver también
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
