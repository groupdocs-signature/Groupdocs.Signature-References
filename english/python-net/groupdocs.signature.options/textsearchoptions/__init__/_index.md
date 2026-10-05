---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the TextSearchOptions class with default values."
type: docs
url: /python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the TextSearchOptions class with default values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Search for text signatures using default options
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

Initializes a new instance of the TextSearchOptions class with a text value.

```python
def __init__(self, text):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| text | `str` | Text of the text signature. |

### See Also
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
