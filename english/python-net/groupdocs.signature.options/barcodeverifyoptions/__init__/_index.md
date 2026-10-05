---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes default verification option for barcode signature."
type: docs
url: /python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes default verification option for barcode signature.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Initializes a default verification option with verification text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Barcode text to verify. |

## __init__ {#encode_type}

Initializes a default verification option with barcode type verification.

```python
def __init__(self, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode type verification. |

## __init__ {#text-encode_type}

Initializes a default verification option with barcode type verification and text.

```python
def __init__(self, text, encode_type):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Barcode text to verify. |
| encode_type | `BarcodeType` | Barcode type verification. |

### See Also
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
