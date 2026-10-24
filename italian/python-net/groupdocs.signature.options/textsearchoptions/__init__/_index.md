---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe TextSearchOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe TextSearchOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Cerca firme di testo usando le opzioni predefinite
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Inizializza una nuova istanza della classe TextSearchOptions con un valore di testo.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo della firma di testo. |

### Vedi anche
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
