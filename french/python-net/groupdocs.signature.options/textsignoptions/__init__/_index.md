---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe TextSignOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe TextSignOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initialise une nouvelle instance de la classe TextSignOptions avec du texte.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte de signature. |

### Exemple

```python
from groupdocs.signature.options import TextSignOptions

# Créer une option de signature texte avec le texte de signature souhaité
options = TextSignOptions("John Smith")
```

### Voir aussi
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
