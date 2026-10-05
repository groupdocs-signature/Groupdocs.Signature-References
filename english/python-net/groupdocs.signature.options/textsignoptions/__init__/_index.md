---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the TextSignOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the TextSignOptions class with default values.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Initializes a new instance of the TextSignOptions class with text.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Signature text. |

### Example

```python
from groupdocs.signature.options import TextSignOptions

# Create a text signature option with the desired signature text
options = TextSignOptions("John Smith")
```

### See Also
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
