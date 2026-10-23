---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert die Spreadsheet-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert."
type: docs
url: /de/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Initialisiert die Spreadsheet-Metadaten-Signatur mit vordefiniertem Namen und leerem Wert.

```python
def __init__(self, name):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name der Spreadsheet‑Metadaten‑Signatur. |

## __init__ {#name-value}

Initialisiert eine Spreadsheet-Metadaten-Signatur mit vordefinierten Werten.

```python
def __init__(self, name, value):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| name | `str` | Name des Metadaten-Signaturobjekts. |
| value | `Any` | Wert der Metadaten-Signatur. |

### Beispiel

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# Metadaten‑Signaturen für ein Tabellenblatt erstellen
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### Siehe auch
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
