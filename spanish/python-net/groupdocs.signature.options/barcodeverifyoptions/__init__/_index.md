---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa la opción de verificación predeterminada para la firma de código de barras."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa la opción de verificación predeterminada para la firma de código de barras.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Inicializa una opción de verificación predeterminada con texto de verificación.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto del código de barras a verificar. |

## __init__ {#encode_type}

Inicializa una opción de verificación predeterminada con verificación de tipo de código de barras.

```python
def __init__(self, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| encode_type | `BarcodeType` | Verificación del tipo de código de barras. |

## __init__ {#text-encode_type}

Inicializa una opción de verificación predeterminada con verificación de tipo de código de barras y texto.

```python
def __init__(self, text, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto del código de barras a verificar. |
| encode_type | `BarcodeType` | Verificación del tipo de código de barras. |

### Ver también
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
