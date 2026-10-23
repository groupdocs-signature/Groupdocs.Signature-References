---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Ein Suchoptionen‑Objekt mit Standardeinstellungen erstellen
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit dem Encode-Typ-Wert.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| encode_type | `BarcodeType` | Gibt den Barcode‑Kodierungstyp an. |

## __init__ {#encode_type-text}

Initialisiert eine neue Instanz der BarcodeSearchOptions Klasse mit Encode-Typ- und Textwerten.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| encode_type | `BarcodeType` | Gibt den Barcode‑Kodierungstyp an. |
| text | `str` | Text der Barcode‑Signatur festlegen. |

### Siehe auch
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
