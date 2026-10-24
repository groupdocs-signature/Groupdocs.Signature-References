---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe QRCodeSignOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe QRCodeSignOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inizializza un'istanza di opzioni di firma QR code con il testo specificato.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo della firma. |

### Esempio

```python
from groupdocs.signature.options import QrCodeSignOptions

# Crea opzioni di firma QR code con il testo desiderato
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Inizializza una nuova istanza della classe QrCodeSignOptions con il testo.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo QRCode. |
| encode_type | `QrCodeType` | Tipo di codifica QRCode. |

### Esempio

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Vedi anche
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
