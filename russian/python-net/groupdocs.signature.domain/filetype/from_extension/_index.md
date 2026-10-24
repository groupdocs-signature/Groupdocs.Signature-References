---
title: "метод from_extension"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Отображает расширение файла на тип файла."
type: docs
url: /ru/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

Отображает расширение файла на тип файла.

```python
def from_extension(cls, extension):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| extension | `str` | Расширение файла (включая точку "."). |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| Вызывает | Описание |
| :- | :- |
| `ValueError` | Вызывается, когда `extension` равно null или пустой строке. |

### Пример

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### См. также
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
