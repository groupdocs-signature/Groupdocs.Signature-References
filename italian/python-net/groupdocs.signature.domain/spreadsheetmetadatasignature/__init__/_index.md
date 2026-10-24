---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza la firma dei metadati del foglio di calcolo con nome predefinito e valore vuoto."
type: docs
url: /it/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Inizializza la firma dei metadati del foglio di calcolo con nome predefinito e valore vuoto.

```python
def __init__(self, name):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| name | `str` | Nome della firma di metadati del foglio di calcolo. |

## __init__ {#name-value}

Inizializza una firma dei metadati del foglio di calcolo con valori predefiniti.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Crea firme di metadati per un foglio di calcolo
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Vedi anche
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
