---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase TextSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase TextSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Inicializa una nueva instancia de la clase TextSignOptions con texto.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto de la firma. |

### Ejemplo

```python
from groupdocs.signature.options import TextSignOptions

# Crear una opción de firma de texto con el texto de firma deseado
options = TextSignOptions("John Smith")
```

### Ver también
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
