---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe Padding avec des valeurs zéro."
type: docs
url: /fr/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe Padding avec des valeurs zéro.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature.domain import Padding

# Créer un objet de remplissage avec des valeurs par défaut (zéro)
default_padding = Padding()
```

## __init__ {#all}

Initialise une nouvelle instance de la classe Padding en utilisant la taille de remplissage fournie pour tous les bords.

```python
def __init__(self, all):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| all | `int` | Le nombre d'unités de mesure à utiliser pour le remplissage de tous les bords. |

### Exemple

```python
# Remplissage uniforme de 5 unités sur tous les côtés
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Initialise une nouvelle instance de la classe Padding en utilisant les tailles de remplissage fournies.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| left | `int` | La taille du remplissage left. |
| right | `int` | La taille du remplissage right. |
| top | `int` | La taille du remplissage top. |
| bottom | `int` | La taille du remplissage bottom. |

### Exemple

```python
from groupdocs.signature.domain import Padding

# Créer un remplissage avec des décalages right et bottom
margin = Padding(right=40, bottom=60)
```

### Voir aussi
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
