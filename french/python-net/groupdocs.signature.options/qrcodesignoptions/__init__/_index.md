---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe QRCodeSignOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialise une instance d'options de signature QR‑code avec le texte spécifié.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte de signature. |

### Exemple

```python
from groupdocs.signature.options import QrCodeSignOptions

# Créer des options de signature QR code avec le texte souhaité
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Initialise une nouvelle instance de la classe QrCodeSignOptions avec du texte.

```python
def __init__(self, text, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte QRCode. |
| encode_type | `QrCodeType` | Type d'encodage QRCode. |

### Exemple

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Voir aussi
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
