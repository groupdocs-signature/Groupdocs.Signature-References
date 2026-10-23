---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Barcode‑Text. |

### Beispiel

```python
from groupdocs.signature.options import BarcodeSignOptions

# Erstellen Sie Barcode‑Signatur‑Optionen mit dem gewünschten Text
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Initialisiert eine neue Instanz der Klasse BarcodeSignOptions mit Text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Barcode‑Text. |
| encode_type | `BarcodeType` | Barcode‑Kodierungstyp. |

### Beispiel

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Erstellen Sie Barcode‑Signatur‑Optionen mit Text und Typ
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Siehe auch
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
