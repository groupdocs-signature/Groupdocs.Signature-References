---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Barcode-tekst. |

### Voorbeeld

```python
from groupdocs.signature.options import BarcodeSignOptions

# Maak barcode-handtekeningopties met de gewenste tekst
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Initialiseert een nieuw exemplaar van de BarcodeSignOptions klasse met tekst.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Barcode-tekst. |
| encode_type | `BarcodeType` | Barcode‑coderingstype. |

### Voorbeeld

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Maak barcode-handtekeningopties met tekst en type
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Zie ook
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
