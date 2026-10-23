---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der QRCodeSignOptions-Klasse mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der QRCodeSignOptions-Klasse mit Standardwerten.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialisiert eine QR-Code-Signaturoptions-Instanz mit dem angegebenen Text.

```python
def __init__(self, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | Signaturtext. |

### Beispiel

```python
from groupdocs.signature.options import QrCodeSignOptions

# QR‑Code‑Signaturoptionen mit dem gewünschten Text erstellen
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Initialisiert eine neue Instanz der QrCodeSignOptions-Klasse mit Text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | `str` | QRCode‑Text. |
| encode_type | `QrCodeType` | QRCode‑Kodierungstyp. |

### Beispiel

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Siehe auch
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
