---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise l'option de vérification par défaut pour la signature de code-barres."
type: docs
url: /fr/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise l'option de vérification par défaut pour la signature de code-barres.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Initialise une option de vérification par défaut avec le texte de vérification.

```python
def __init__(self, text):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte du code-barres à vérifier. |

## __init__ {#encode_type}

Initialise une option de vérification par défaut avec la vérification du type de code-barres.

```python
def __init__(self, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Vérification du type de code-barres. |

## __init__ {#text-encode_type}

Initialise une option de vérification par défaut avec la vérification du type de code-barres et du texte.

```python
def __init__(self, text, encode_type):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| text | `str` | Texte du code-barres à vérifier. |
| encode_type | `BarcodeType` | Vérification du type de code-barres. |

### Voir aussi
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
