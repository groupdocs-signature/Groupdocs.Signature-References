---
title: "from_extension yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Dosya uzantısını dosya türüne eşler."
type: docs
url: /tr/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Dosya uzantısını dosya türüne eşler.

```python
def from_extension(cls, extension):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extension | `str` | Dosya uzantısı (nokta "." dahil). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Kaldırır | Açıklama |
| :- | :- |
| `ValueError` | `extension` null veya boş bir dize olduğunda ortaya çıkar. |

### Örnek

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Ayrıca Bakınız
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
