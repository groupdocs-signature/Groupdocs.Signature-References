---
title: __init__ constructor
second_title: GroupDocs.Signature for Python via .NET API References
description: "Initializes a new instance of the Padding class with zero values."
type: docs
url: /python-net/groupdocs.signature.domain/padding/__init__/
is_root: false
weight: 10
---


## __init__

Initializes a new instance of the Padding class with zero values.

```python
def __init__(self):
    ...
```

### Example

```python
from groupdocs.signature.domain import Padding

# Create a padding object with default (zero) values
default_padding = Padding()
```

## __init__ {#all}

Initializes a new instance of the Padding class using the supplied padding size for all edges.

```python
def __init__(self, all):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| all | `int` | The number of measure units to be used for padding for all edges. |

### Example

```python
# Uniform padding of 5 units on all sides
margin = Padding(5)
```

## __init__ {#left-right-top-bottom}

Initializes a new instance of the Padding class using the supplied padding sizes.

```python
def __init__(self, left, right, top, bottom):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| left | `int` | The left padding size. |
| right | `int` | The right padding size. |
| top | `int` | The top padding size. |
| bottom | `int` | The bottom padding size. |

### Example

```python
from groupdocs.signature.domain import Padding

# Create a padding with right and bottom offsets
margin = Padding(right=40, bottom=60)
```

### See Also
* class [`Padding`](/signature/python-net/groupdocs.signature.domain/padding/)
