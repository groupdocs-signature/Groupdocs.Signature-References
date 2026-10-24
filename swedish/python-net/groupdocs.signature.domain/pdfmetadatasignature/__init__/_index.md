---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en PDF-metadata-signatur med ett fördefinierat namn och ett tomt värde."
type: docs
url: /sv/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initierar en PDF-metadata-signatur med ett fördefinierat namn och ett tomt värde.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | PDF‑metadata‑signaturnamn. |

## __init__ {#name-value}

Initierar en PDF-metadata-signatur med fördefinierade värden.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på metadata‑signaturobjektet. |
| value | `Any` | Värde för metadata‑signaturen. |

### Exempel

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

Initierar en PDF-metadata-signatur med fördefinierade värden.

```python
def __init__(self, name, value, tag):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på metadata‑signaturobjektet. |
| value | `Any` | Värde för metadata‑signaturen. |
| tag | `str` | Prefix‑tagg för metadata‑signaturen. |

### Exempel

```python
from groupdocs.signature.domain import PdfMetadataSignature

# Skapa en metadata‑signatur för PDF‑författaren
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# Skapa en metadata‑signatur för skapelsedatumet
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# Skapa en metadata‑signatur för en numerisk identifierare
id_sig = PdfMetadataSignature("DocumentId", 123456)

# Skapa en metadata‑signatur för ett flyttal
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### Se även
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
