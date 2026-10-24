---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza l'opzione di verifica predefinita per la firma barcode."
type: docs
url: /it/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza l'opzione di verifica predefinita per la firma barcode.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Inizializza un'opzione di verifica predefinita con testo di verifica.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo del codice a barre da verificare. |

## __init__ {#encode_type}

Inizializza un'opzione di verifica predefinita con verifica del tipo di barcode.

```python
def __init__(self, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| encode_type | `BarcodeType` | Verifica del tipo di codice a barre. |

## __init__ {#text-encode_type}

Inizializza un'opzione di verifica predefinita con verifica del tipo di codice a barre e testo.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo del codice a barre da verificare. |
| encode_type | `BarcodeType` | Verifica del tipo di codice a barre. |

### Vedi anche
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
