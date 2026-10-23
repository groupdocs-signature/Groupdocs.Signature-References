---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe TextSearchOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Rechercher des signatures texte en utilisant les options par défaut
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Initialise une nouvelle instance de la classe TextSearchOptions avec une valeur de texte.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte de la signature texte. |

### Voir aussi
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
