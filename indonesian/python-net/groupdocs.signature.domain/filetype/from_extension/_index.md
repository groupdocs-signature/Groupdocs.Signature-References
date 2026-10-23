---
title: "metode from_extension"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Memetakan ekstensi file ke tipe file."
type: docs
url: /id/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Memetakan ekstensi file ke tipe file.

```python
def from_extension(cls, extension):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extension | `str` | Ekstensi file (termasuk titik "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Melepaskan | Deskripsi |
| :- | :- |
| `ValueError` | Dilempar ketika `extension` bernilai null atau string kosong. |

### Contoh

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### Lihat Juga
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
