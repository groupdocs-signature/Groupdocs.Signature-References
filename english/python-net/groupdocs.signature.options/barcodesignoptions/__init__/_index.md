---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the BarcodeSignOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the BarcodeSignOptions class with default values.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initializes a new instance of the BarcodeSignOptions class with text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Barcode text. |

### Example

```python
from groupdocs.signature.options import BarcodeSignOptions

# Create barcode signature options with the desired text
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

Initializes a new instance of the BarcodeSignOptions class with text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Barcode text. |
| encode_type | `BarcodeType` | Barcode encode type. |

### Example

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Create barcode signature options with text and type
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### See Also
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
