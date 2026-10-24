---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase BarcodeSearchOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase BarcodeSearchOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Crear un objeto de opciones de búsqueda con la configuración predeterminada
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Inicializa una nueva instancia de la clase BarcodeSearchOptions con el valor del tipo de codificación.

```python
def __init__(self, encode_type):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| encode_type | `BarcodeType` | Especifica el tipo de codificación del código de barras. |

## __init__ {#encode_type-text}

Inicializa una nueva instancia de la clase BarcodeSearchOptions con los valores del tipo de codificación y texto.

```python
def __init__(self, encode_type, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| encode_type | `BarcodeType` | Especifica el tipo de codificación del código de barras. |
| text | `str` | Establecer el texto de la firma de código de barras. |

### Ver también
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
