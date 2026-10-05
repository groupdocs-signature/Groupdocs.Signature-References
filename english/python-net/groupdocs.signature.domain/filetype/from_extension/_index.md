---
title: from_extension method
second_title: GroupDocs.Signature for Python via .NET API References
description: "Maps file extension to file type."
type: docs
url: /python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Maps file extension to file type.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| extension | `str` | File extension (including the period "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Raises | Description |
| :- | :- |
| `ValueError` | Raised when `extension` is null or empty string. |

### Example

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### See Also
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
