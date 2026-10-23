---
title: "__init__ Konstruktor"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Initialisiert eine neue Instanz der Klasse ImageSignOptions mit Standardwerten."
type: docs
url: /de/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialisiert eine neue Instanz der Klasse ImageSignOptions mit Standardwerten.

```python
def __init__(self):
    ...
```

### Beispiel

```python
from groupdocs.signature.options import ImageSignOptions

# Erstelle Bildsignatur-Optionen mithilfe eines Bilddateipfads
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Initialisiert ImageSignOptions mit einer Bilddatei.

```python
def __init__(self, image_file_path):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_file_path | `str` | Bilddateipfad. |

### Beispiel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # Konfiguriere hier zusätzliche Optionen, z. B. Position, Größe usw.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Initialisiert eine neue ImageSignOptions-Instanz mit einem Bild-Stream.

```python
def __init__(self, image_stream):
    ...
```

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Bildstrom. |

### Beispiel

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

### Siehe auch
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
