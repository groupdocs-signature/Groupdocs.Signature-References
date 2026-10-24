---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een PDF-metadatahandtekening met een vooraf gedefinieerde naam en een lege waarde."
type: docs
url: /nl/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialiseert een PDF-metadatahandtekening met een vooraf gedefinieerde naam en een lege waarde.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | PDF metadata‑handtekeningnaam. |

## __init__ {#name-value}

Initialiseert een PDF-metadatahandtekening met vooraf gedefinieerde waarden.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Naam van het metadata‑handtekeningobject. |
| value | `Any` | Waarde van de metadata‑handtekening. |

### Voorbeeld

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

Initialiseert een PDF-metadatahandtekening met vooraf gedefinieerde waarden.

```python
def __init__(self, name, value, tag):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Naam van het metadata‑handtekeningobject. |
| value | `Any` | Waarde van de metadata‑handtekening. |
| tag | `str` | Voorvoegsel‑tag van de metadata‑handtekening. |

### Voorbeeld

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Maak een metadata‑handtekening voor de PDF‑auteur
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Maak een metadata‑handtekening voor de creatiedatum
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Maak een metadata‑handtekening voor een numerieke identifier
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Maak een metadata‑handtekening voor een floating‑point‑waarde
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Zie ook
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
