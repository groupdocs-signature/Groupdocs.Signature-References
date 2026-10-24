---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar Spreadsheet Metadata Signature med fördefinierat namn och tomt värde."
type: docs
url: /sv/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initierar Spreadsheet Metadata Signature med fördefinierat namn och tomt värde.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| name | `str` | Namn på kalkylbladsmetadata‑signatur. |

## __init__ {#name-value}

Initierar en Spreadsheet Metadata Signature med fördefinierade värden.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Skapa metadata‑signaturer för ett kalkylblad
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Se även
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
