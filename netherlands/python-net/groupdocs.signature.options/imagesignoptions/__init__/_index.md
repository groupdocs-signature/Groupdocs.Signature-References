---
title: "__init__-constructor"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Initialiseert een nieuw exemplaar van de ImageSignOptions klasse met standaardwaarden."
type: docs
url: /nl/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initialiseert een nieuw exemplaar van de ImageSignOptions klasse met standaardwaarden.

```python
def __init__(self):
    ...
```

### Voorbeeld

```python
from groupdocs.signature.options import ImageSignOptions

# Maak afbeeldingshandtekeningopties aan met een afbeeldingsbestandspad.
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Initialiseert ImageSignOptions met een afbeeldingsbestand.

```python
def __init__(self, image_file_path):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_file_path | `str` | Afbeeldingsbestandspad. |

### Voorbeeld

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # configureer hier extra opties, bijv. positie, grootte, enz.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Initialiseert een nieuw ImageSignOptions exemplaar met een afbeeldingsstroom.

```python
def __init__(self, image_stream):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Afbeeldingsstroom. |

### Voorbeeld

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

### Zie ook
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
