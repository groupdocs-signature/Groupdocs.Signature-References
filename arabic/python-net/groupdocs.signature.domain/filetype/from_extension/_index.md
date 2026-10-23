---
title: "طريقة from_extension"
second_title: "مراجع API لـ GroupDocs.Signature للبايثون عبر .NET"
description: "يربط امتداد الملف بنوع الملف."
type: docs
url: /ar/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

يربط امتداد الملف بنوع الملف.

```python
def from_extension(cls, extension):
    ...
```

| معامل | نوع | الوصف |
| :- | :- | :- |
| extension | `str` | امتداد الملف (بما في ذلك النقطة "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| يُثير | الوصف |
| :- | :- |
| `ValueError` | يتم رفع الاستثناء عندما تكون `extension` فارغة أو null. |

### مثال

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### انظر أيضًا
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
