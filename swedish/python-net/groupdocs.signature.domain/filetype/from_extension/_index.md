---
title: "from_extension-metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Kopplar filändelse till filtyp."
type: docs
url: /sv/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Kopplar filändelse till filtyp.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extension | `str` | Filändelse (inklusive punkten "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Utlöser | Beskrivning |
| :- | :- |
| `ValueError` | Utlöst när `extension` är null eller en tom sträng. |

### Exempel

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Se även
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
