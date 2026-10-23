---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe BarcodeSearchOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe BarcodeSearchOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Créer un objet d'options de recherche avec les paramètres par défaut
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Initialise une nouvelle instance de la classe BarcodeSearchOptions avec la valeur du type d'encodage.

```python
def __init__(self, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Spécifie le type d'encodage du code-barres. |

## __init__ {#encode_type-text}

Initialise une nouvelle instance de la classe BarcodeSearchOptions avec les valeurs du type d'encodage et du texte.

```python
def __init__(self, encode_type, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Spécifie le type d'encodage du code-barres. |
| text | `str` | Définir le texte de la signature de code-barres. |

### Voir aussi
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
