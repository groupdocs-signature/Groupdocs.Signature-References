---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase BarcodeSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inicializa una nueva instancia de la clase BarcodeSignOptions con texto.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto del código de barras. |

### Ejemplo

```python
from groupdocs.signature.options import BarcodeSignOptions

# Crear opciones de firma de código de barras con el texto deseado
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Inicializa una nueva instancia de la clase BarcodeSignOptions con texto.

```python
def __init__(self, text, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto del código de barras. |
| encode_type | `BarcodeType` | Tipo de codificación del código de barras. |

### Ejemplo

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Crear opciones de firma de código de barras con texto y tipo
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Ver también
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
