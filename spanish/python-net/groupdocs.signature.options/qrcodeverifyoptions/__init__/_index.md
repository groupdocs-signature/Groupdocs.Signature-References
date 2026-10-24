---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa las opciones de verificación para firmas QR-Code."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa las opciones de verificación para firmas QR-Code.

```python
def __init__(self):
    ...
```

### Ejemplo

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

Inicializa las opciones de verificación para firmas QR-Code con el texto QR-code especificado.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto QR-code a verificar. |

### Ejemplo

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Crear opciones y establecer el texto QR-code a verificar
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Inicializa las opciones de verificación para firmas QR-Code con texto y tipo de codificación QR-Code a verificar.

```python
def __init__(self, text, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto a verificar. |
| encode_type | `QrCodeType` | Tipo de codificación. |

### Ejemplo

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Ver también
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
