---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase QRCodeSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inicializa una instancia de QrCodeSignOptions con el texto especificado.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto de la firma. |

### Ejemplo

```python
from groupdocs.signature.options import QrCodeSignOptions

# Crear opciones de firma QR code con el texto deseado
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Inicializa una nueva instancia de la clase QrCodeSignOptions con texto.

```python
def __init__(self, text, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto QRCode. |
| encode_type | `QrCodeType` | Tipo de codificación QRCode. |

### Ejemplo

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Ver también
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
