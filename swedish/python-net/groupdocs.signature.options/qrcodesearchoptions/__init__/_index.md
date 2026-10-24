---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av QRCodeSearchOptions-klassen med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av QRCodeSearchOptions-klassen med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Initierar en ny instans av QRCodeSearchOptions-klassen med kodningstypvärde.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| encode_type | `QrCodeType` | Anger QR-Code-kodningstyp. |

## __init__ {#encode_type-text}

Initierar en ny instans av klassen QRCodeSearchOptions med kodningstyp och textvärden.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| encode_type | `QrCodeType` | Anger QR-Code-kodningstyp. |
| text | `str` | Ange text för QR-Code-signatur. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Se även
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
