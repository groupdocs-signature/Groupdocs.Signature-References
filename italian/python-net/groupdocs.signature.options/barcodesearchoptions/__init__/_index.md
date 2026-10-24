---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe BarcodeSearchOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe BarcodeSearchOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Crea un oggetto di opzioni di ricerca con le impostazioni predefinite
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Inizializza una nuova istanza della classe BarcodeSearchOptions con il valore del tipo di codifica.

```python
def __init__(self, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| encode_type | `BarcodeType` | Specifica il tipo di codifica del Barcode. |

## __init__ {#encode_type-text}

Inizializza una nuova istanza della classe BarcodeSearchOptions con i valori del tipo di codifica e del testo.

```python
def __init__(self, encode_type, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| encode_type | `BarcodeType` | Specifica il tipo di codifica del Barcode. |
| text | `str` | Imposta il testo della firma Barcode. |

### Vedi anche
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
