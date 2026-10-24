---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen QRCodeSignOptions med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av klassen QRCodeSignOptions med standardvärden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initierar en QR-kod signaturalternativ-instans med den angivna texten.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Signaturtext. |

### Exempel

```python
from groupdocs.signature.options import QrCodeSignOptions

# Skapa QR‑kod signaturalternativ med önskad text
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Initierar en ny instans av klassen QrCodeSignOptions med text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | QRCode‑text. |
| encode_type | `QrCodeType` | QRCode‑kodningstyp. |

### Exempel

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Se även
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
