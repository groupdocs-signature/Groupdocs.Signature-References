---
title: "__init__-konstruktor"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Initierar en ny instans av klassen ImageSignOptions med standardvärden."
type: docs
url: /sv/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initierar en ny instans av klassen ImageSignOptions med standardvärden.

```python
def __init__(self):
    ...
```

### Exempel

```python
from groupdocs.signature.options import ImageSignOptions

# Skapa bildsignaturalternativ med en bildfilssökväg
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Initierar ImageSignOptions med en bildfil.

```python
def __init__(self, image_file_path):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_file_path | `str` | Sökväg till bildfil. |

### Exempel

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # konfigurera ytterligare alternativ här, t.ex. position, storlek osv.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Initierar en ny ImageSignOptions-instans med en bildström.

```python
def __init__(self, image_stream):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Bildström. |

### Exempel

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

### Se även
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
