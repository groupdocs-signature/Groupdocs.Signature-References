---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert verificatieopties voor QR-Code-handtekeningen."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert verificatieopties voor QR-Code-handtekeningen.

```python
def __init__(self):
    ...
```

### Voorbeeld

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

Initialiseert verificatieopties voor QR-Code-handtekeningen met de opgegeven QR-code-tekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | QR-code tekst om te verifiëren. |

### Voorbeeld

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Maak opties aan en stel de QR-code tekst in om te verifiëren
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Initialiseert verificatieopties voor QR-Code-handtekeningen met tekst en QR-Code-encoderingstype om te verifiëren.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Tekst om te verifiëren. |
| encode_type | `QrCodeType` | Type codering. |

### Voorbeeld

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Zie ook
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
