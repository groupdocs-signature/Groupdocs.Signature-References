---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe BarcodeSignOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe BarcodeSignOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte du code‑barres. |

### Exemple

```python
from groupdocs.signature.options import BarcodeSignOptions

# Créez des options de signature de code‑barres avec le texte souhaité
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Initialise une nouvelle instance de la classe BarcodeSignOptions avec du texte.

```python
def __init__(self, text, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte du code‑barres. |
| encode_type | `BarcodeType` | Type d’encodage du code‑barres. |

### Exemple

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Créez des options de signature de code‑barres avec le texte et le type
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Voir aussi
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
