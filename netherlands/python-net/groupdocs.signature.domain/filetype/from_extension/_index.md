---
title: "from_extension‑methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Koppelt bestandsextensie aan bestandstype."
type: docs
url: /nl/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Koppelt bestandsextensie aan bestandstype.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extension | `str` | Bestandsextensie (inclusief de punt "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Verhoogt | Beschrijving |
| :- | :- |
| `ValueError` | Wordt opgegooid wanneer `extension` null of een lege tekenreeks is. |

### Voorbeeld

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Zie ook
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
