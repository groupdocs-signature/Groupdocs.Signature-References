---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza le opzioni di verifica per le firme QR-Code."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza le opzioni di verifica per le firme QR-Code.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Inizializza le opzioni di verifica per le firme QR-Code con il testo QR-code specificato.

```python
def __init__(self, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo QR-code da verificare. |

### Esempio

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Crea opzioni e imposta il testo QR-code da verificare
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Inizializza le opzioni di verifica per le firme QR-Code con testo e tipo di codifica QR-Code da verificare.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | `str` | Testo da verificare. |
| encode_type | `QrCodeType` | Tipo di codifica. |

### Esempio

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Vedi anche
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
