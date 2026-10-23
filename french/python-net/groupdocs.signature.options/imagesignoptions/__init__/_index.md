---
title: "constructeur __init__"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut."
type: docs
url: /fr/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialise une nouvelle instance de la classe ImageSignOptions avec les valeurs par défaut.

```python
def __init__(self):
    ...
```

### Exemple

```python
from groupdocs.signature.options import ImageSignOptions

# Créer des options de signature d'image en utilisant un chemin de fichier image
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Initialise ImageSignOptions avec un fichier image.

```python
def __init__(self, image_file_path):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_file_path | `str` | Chemin du fichier image. |

### Exemple

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # configurer des options supplémentaires ici, p. ex. position, taille, etc.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Initialise une nouvelle instance ImageSignOptions avec un flux d'image.

```python
def __init__(self, image_stream):
    ...
```

| Paramètre | Type | Description |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Flux d'image. |

### Exemple

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

### Voir aussi
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
