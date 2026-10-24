---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuwe instantie van de QRCodeSearchOptions‑klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuwe instantie van de QRCodeSearchOptions‑klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Initialiseert een nieuwe instantie van de QRCodeSearchOptions‑klasse met een encode‑typewaarde.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specificeert het QR-Code-codeertype. |

## __init__ {#encode_type-text}

Initialiseert een nieuw exemplaar van de QRCodeSearchOptions‑klasse met coderings‑type en tekstwaarden.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specificeert het QR-Code-codeertype. |
| text | `str` | Stel de tekst van de QR-Code-handtekening in. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Zie ook
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
