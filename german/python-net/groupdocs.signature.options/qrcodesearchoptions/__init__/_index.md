---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit dem Wert für den Kodierungstyp.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| encode_type | `QrCodeType` | Gibt den QR‑Code‑Kodierungstyp an. |

## __init__ {#encode_type-text}

Initialisiert eine neue Instanz der Klasse QRCodeSearchOptions mit den Werten für Kodierungstyp und Text.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| encode_type | `QrCodeType` | Gibt den QR‑Code‑Kodierungstyp an. |
| text | `str` | Setzt den Text der QR‑Code‑Signatur. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Siehe auch
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
