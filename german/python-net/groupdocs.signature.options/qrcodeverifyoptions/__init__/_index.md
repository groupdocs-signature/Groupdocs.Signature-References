---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen.

```python
def __init__(self):
    ...
```

### Beispiel

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

Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen mit dem angegebenen QR-Code‑Text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | QR-Code‑Text zur Überprüfung. |

### Beispiel

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Optionen erstellen und den zu überprüfenden QR-Code‑Text festlegen
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Initialisiert Verifizierungsoptionen für QR-Code‑Signaturen mit Text und QR-Code‑Kodierungstyp zur Verifizierung.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Zu überprüfender Text. |
| encode_type | `QrCodeType` | Kodierungstyp. |

### Beispiel

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Siehe auch
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
