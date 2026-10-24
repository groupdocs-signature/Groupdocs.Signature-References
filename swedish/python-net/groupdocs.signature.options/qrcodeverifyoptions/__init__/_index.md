---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar verifieringsalternativ för QR‑Kod‑signaturer."
type: docs
url: /sv/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar verifieringsalternativ för QR‑Kod‑signaturer.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Initierar verifieringsalternativ för QR‑Kod‑signaturer med den angivna QR‑kodtexten.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | QR‑kodtext att verifiera. |

### Exempel

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Skapa alternativ och ange QR‑kodtexten att verifiera
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Initierar verifieringsalternativ för QR‑Kod‑signaturer med text och QR‑Kod‑kodningstyp att verifiera.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | `str` | Text att verifiera. |
| encode_type | `QrCodeType` | Kodningstyp. |

### Exempel

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Se även
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
