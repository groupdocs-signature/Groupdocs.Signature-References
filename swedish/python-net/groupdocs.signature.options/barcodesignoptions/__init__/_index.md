---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av BarcodeSignOptions-klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av BarcodeSignOptions-klassen med standardvärden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initierar en ny instans av BarcodeSignOptions-klassen med text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Streckkodstext. |

### Exempel

```python
from groupdocs.signature.options import BarcodeSignOptions

# Skapa alternativ för streckkodssignatur med önskad text
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Initierar en ny instans av BarcodeSignOptions-klassen med text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Streckkodstext. |
| encode_type | `BarcodeType` | Streckkodskodningstyp. |

### Exempel

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Skapa alternativ för streckkodssignatur med text och typ
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Se även
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
