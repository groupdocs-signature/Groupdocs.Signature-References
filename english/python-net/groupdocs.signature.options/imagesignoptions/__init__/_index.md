---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the ImageSignOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the ImageSignOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature.options import ImageSignOptions

# Create image signature options using an image file path
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

Initializes ImageSignOptions with an image file.

```python
def __init__(self, image_file_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_file_path | `str` | Image file path. |

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # configure additional options here, e.g. position, size, etc.
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

Initializes a new ImageSignOptions instance with an image stream.

```python
def __init__(self, image_stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | Image stream. |

### Example

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

### See Also
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
