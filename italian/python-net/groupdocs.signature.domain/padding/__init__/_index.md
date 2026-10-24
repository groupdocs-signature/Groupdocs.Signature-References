---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe Padding con valori zero."
type: docs
url: /it/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe Padding con valori zero.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature.domain import Padding

# Crea un oggetto di padding con valori predefiniti (zero)
default_padding = Padding()
```

## __init__ {#all}

Inizializza una nuova istanza della classe Padding usando la dimensione di padding fornita per tutti i bordi.

```python
def __init__(self, all):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| all | `int` | Il numero di unità di misura da utilizzare per il padding su tutti i bordi. |

### Esempio

```python
# Padding uniforme di 5 unità su tutti i lati
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Inizializza una nuova istanza della classe Padding usando le dimensioni di padding fornite.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left | `int` | La dimensione del padding sinistro. |
| right | `int` | La dimensione del padding destro. |
| top | `int` | La dimensione del padding superiore. |
| bottom | `int` | La dimensione del padding inferiore. |

### Esempio

```python
from groupdocs.signature.domain import Padding

# Crea un padding con offset destro e inferiore
margin = Padding(right=40, bottom=60)
```

### Vedi anche
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
