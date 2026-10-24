---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de Padding-klasse met nulwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de Padding-klasse met nulwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature.domain import Padding

# Maak een padding‑object met standaard (nul) waarden
default_padding = Padding()
```

## __init__ {#all}

Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven opvulgrootte voor alle randen.

```python
def __init__(self, all):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| all | `int` | Het aantal meeteenheden dat moet worden gebruikt voor padding voor alle randen. |

### Voorbeeld

```python
# Gelijke opvulling van 5 eenheden aan alle zijden
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Initialiseert een nieuw exemplaar van de Padding-klasse met de opgegeven opvulgroottes.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| left | `int` | De left padding‑grootte. |
| right | `int` | De right padding‑grootte. |
| top | `int` | De top padding‑grootte. |
| bottom | `int` | De bottom padding‑grootte. |

### Voorbeeld

```python
from groupdocs.signature.domain import Padding

# Maak een padding met right‑ en bottom‑offsets
margin = Padding(right=40, bottom=60)
```

### Zie ook
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
