---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe QRCodeSearchOptions con valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe QRCodeSearchOptions con valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Inizializza una nuova istanza della classe QRCodeSearchOptions con il valore del tipo di codifica.

```python
def __init__(self, encode_type):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specifica il tipo di codifica QR-Code. |

## __init__ {#encode_type-text}

Inizializza una nuova istanza della classe QRCodeSearchOptions con i valori di tipo di codifica e testo.

```python
def __init__(self, encode_type, text):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| encode_type | `QrCodeType` | Specifica il tipo di codifica QR-Code. |
| text | `str` | Imposta il testo della firma QR-Code. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Vedi anche
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
