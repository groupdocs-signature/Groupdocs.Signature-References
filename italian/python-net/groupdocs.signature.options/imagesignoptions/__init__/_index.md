---
title: "costruttore __init__"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Inizializza una nuova istanza della classe ImageSignOptions con i valori predefiniti."
type: docs
url: /it/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Inizializza una nuova istanza della classe ImageSignOptions con i valori predefiniti.

```python
def __init__(self):
    ...
```

### Esempio

```python
from groupdocs.signature.options import ImageSignOptions

# Crea opzioni di firma immagine usando un percorso file immagine
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Inizializza ImageSignOptions con un file immagine.

```python
def __init__(self, image_file_path):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_file_path | `str` | Percorso del file immagine. |

### Esempio

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # configura ulteriori opzioni qui, ad esempio posizione, dimensione, ecc.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Inizializza una nuova istanza di ImageSignOptions con un flusso di immagine.

```python
def __init__(self, image_stream):
    ...
```

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Flusso immagine. |

### Esempio

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

### Vedi anche
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
