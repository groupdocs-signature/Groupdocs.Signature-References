---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe BarcodeSignOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe BarcodeSignOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inizializza una nuova istanza della classe BarcodeSignOptions con testo.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo Barcode. |

### Esempio

```python
from groupdocs.signature.options import BarcodeSignOptions

# Crea opzioni di firma barcode con il testo desiderato
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Inizializza una nuova istanza della classe BarcodeSignOptions con testo.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo Barcode. |
| encode_type | `BarcodeType` | Tipo di codifica Barcode. |

### Esempio

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Crea opzioni di firma barcode con testo e tipo
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Vedi anche
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
