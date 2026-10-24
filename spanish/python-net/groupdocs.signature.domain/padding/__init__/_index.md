---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase Padding con valores cero."
type: docs
url: /es/python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase Padding con valores cero.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature.domain import Padding

# Crear un objeto de relleno con valores predeterminados (cero)
default_padding = Padding()
```

## __init__ {#all}

Inicializa una nueva instancia de la clase Padding usando el tamaño de relleno suministrado para todos los bordes.

```python
def __init__(self, all):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| all | `int` | El número de unidades de medida que se usarán para el relleno en todos los bordes. |

### Ejemplo

```python
# Relleno uniforme de 5 unidades en todos los lados
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Inicializa una nueva instancia de la clase Padding usando los tamaños de relleno suministrados.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| left | `int` | El tamaño del relleno izquierdo. |
| right | `int` | El tamaño del relleno derecho. |
| top | `int` | El tamaño del relleno superior. |
| bottom | `int` | El tamaño del relleno inferior. |

### Ejemplo

```python
from groupdocs.signature.domain import Padding

# Crear un relleno con desplazamientos derecho e inferior
margin = Padding(right=40, bottom=60)
```

### Ver también
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
