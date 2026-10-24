---
title: "constructor __init__"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Inicializa una nueva instancia de la clase ImageSignOptions con valores predeterminados."
type: docs
url: /es/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inicializa una nueva instancia de la clase ImageSignOptions con valores predeterminados.

```python
def __init__(self):
    ...
```

### Ejemplo

```python
from groupdocs.signature.options import ImageSignOptions

# Crear opciones de firma de imagen usando una ruta de archivo de imagen
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Inicializa ImageSignOptions con un archivo de imagen.

```python
def __init__(self, image_file_path):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_file_path | `str` | Ruta del archivo de imagen. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # configure opciones adicionales aquí, p. ej. posición, tamaño, etc.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Inicializa una nueva instancia de ImageSignOptions con un flujo de imagen.

```python
def __init__(self, image_stream):
    ...
```

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Flujo de imagen. |

### Ejemplo

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### Ver también
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
