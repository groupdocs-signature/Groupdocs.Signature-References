---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Buscar firmas de texto usando opciones predeterminadas
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto.

```python
def __init__(self, text):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | `str` | Texto de la firma de texto. |

### Ver también
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
