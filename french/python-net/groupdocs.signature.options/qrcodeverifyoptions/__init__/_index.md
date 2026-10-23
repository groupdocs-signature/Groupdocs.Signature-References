---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise les options de vérification pour les signatures QR-Code."
type: docs
url: /fr/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise les options de vérification pour les signatures QR-Code.

```python
def __init__(self):
    ...
```

### Exemple

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

Initialise les options de vérification pour les signatures QR-Code avec le texte QR-code spécifié.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte QR-code à vérifier. |

### Exemple

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Créer les options et définir le texte QR-code à vérifier.
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Initialise les options de vérification pour les signatures QR-Code avec le texte et le type d'encodage QR-Code à vérifier.

```python
def __init__(self, text, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte à vérifier. |
| encode_type | `QrCodeType` | Type d'encodage. |

### Exemple

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Voir aussi
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
