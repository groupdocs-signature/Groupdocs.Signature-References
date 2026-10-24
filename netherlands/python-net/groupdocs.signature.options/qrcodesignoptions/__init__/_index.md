---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de QRCodeSignOptions‑klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de QRCodeSignOptions‑klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialiseert een QR‑codehandtekeningopties‑instantie met de opgegeven tekst.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | Handtekeningtekst. |

### Voorbeeld

```python
from groupdocs.signature.options import QrCodeSignOptions

# Maak QR‑codehandtekening‑opties met de gewenste tekst
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Initialiseert een nieuw exemplaar van de QrCodeSignOptions‑klasse met tekst.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | `str` | QRCode‑tekst. |
| encode_type | `QrCodeType` | QRCode‑encodeertype. |

### Voorbeeld

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Zie ook
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
