---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Inicializa una nueva instancia de la clase QRCodeSearchOptions con el valor del tipo de codificación.

```python
def __init__(self, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| encode_type | `QrCodeType` | Especifica el tipo de codificación QR-Code. |

## __init__ {#encode_type-text}

Inicializa una nueva instancia de la clase QRCodeSearchOptions con los valores de tipo de codificación y texto.

```python
def __init__(self, encode_type, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| encode_type | `QrCodeType` | Especifica el tipo de codificación QR-Code. |
| text | `str` | Establece el texto de la firma QR-Code. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Ver también
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
