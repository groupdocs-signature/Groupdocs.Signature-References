---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert die Standard‑Verifizierungsoption für Barcode‑Signatur."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert die Standard‑Verifizierungsoption für Barcode‑Signatur.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Initialisiert eine Standard‑Verifizierungsoption mit Verifizierungstext.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Barcode-Text zur Überprüfung. |

## __init__ {#encode_type}

Initialisiert eine Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode-Typ‑Verifizierung. |

## __init__ {#text-encode_type}

Initialisiert eine Standard‑Verifizierungsoption mit Barcode‑Typ‑Verifizierung und Text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Barcode-Text zur Überprüfung. |
| encode_type | `BarcodeType` | Barcode-Typ‑Verifizierung. |

### Siehe auch
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
