---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the BarcodeSearchOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the BarcodeSearchOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Create a search options object with default settings
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

Initializes a new instance of the BarcodeSearchOptions class with encode type value.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Specifies Barcode encode type. |

## __init__ {#encode_type-text}

Initializes a new instance of the BarcodeSearchOptions class with encode type and text values.

```python
def __init__(self, encode_type, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Specifies Barcode encode type. |
| text | `str` | Set Text of Barcode signature. |

### See Also
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
