---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una firma di metadati PDF con un nome predefinito e un valore vuoto."
type: docs
url: /it/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inizializza una firma di metadati PDF con un nome predefinito e un valore vuoto.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome della firma di metadati PDF. |

## __init__ {#name-value}

Inizializza una firma di metadati PDF con valori predefiniti.

```python
def __init__(self, name, value):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome dell'oggetto firma di metadati. |
| value | `Any` | Valore della firma di metadati. |

### Esempio

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

Inizializza una firma di metadati PDF con valori predefiniti.

```python
def __init__(self, name, value, tag):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome dell'oggetto firma di metadati. |
| value | `Any` | Valore della firma di metadati. |
| tag | `str` | Tag prefisso della firma di metadati. |

### Esempio

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Crea una firma di metadati per l'autore del PDF
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Crea una firma di metadati per la data di creazione
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Crea una firma di metadati per un identificatore numerico
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Crea una firma di metadati per un valore a virgola mobile
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Vedi anche
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
