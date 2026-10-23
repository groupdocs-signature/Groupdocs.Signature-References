---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe QRCodeSearchOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Initialise une nouvelle instance de la classe QRCodeSearchOptions avec la valeur du type d'encodage.

```python
def __init__(self, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| encode_type | `QrCodeType` | Spécifie le type d'encodage QR-Code. |

## __init__ {#encode_type-text}

Initialise une nouvelle instance de la classe QRCodeSearchOptions avec le type d'encodage et les valeurs de texte.

```python
def __init__(self, encode_type, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| encode_type | `QrCodeType` | Spécifie le type d'encodage QR-Code. |
| text | `str` | Définit le texte de la signature QR-Code. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Voir aussi
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
