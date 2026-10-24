---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert Spreadsheet Metadata Signature met een vooraf gedefinieerde naam en een lege waarde."
type: docs
url: /nl/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialiseert Spreadsheet Metadata Signature met een vooraf gedefinieerde naam en een lege waarde.

```python
def __init__(self, name):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| name | `str` | Spreadsheet Metadata Signature naam. |

## __init__ {#name-value}

Initialiseert een Spreadsheet Metadata Signature met vooraf gedefinieerde waarden.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Maak metadata‑handtekeningen voor een spreadsheet
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Zie ook
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
