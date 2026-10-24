---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe TextSignOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe TextSignOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inizializza una nuova istanza della classe TextSignOptions con testo.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo della firma. |

### Esempio

```python
from groupdocs.signature.options import TextSignOptions

# Crea un'opzione di firma testuale con il testo della firma desiderato
options = TextSignOptions("John Smith")
```

### Vedi anche
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
