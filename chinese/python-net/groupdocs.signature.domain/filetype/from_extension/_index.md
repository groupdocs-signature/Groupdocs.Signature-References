---
title: "from_extension 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "将文件扩展名映射到文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

将文件扩展名映射到文件类型。

```python
def from_extension(cls, extension):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extension | `str` | 文件扩展名（包括句点 “.”）。 |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| 引发 | 描述 |
| :- | :- |
| `ValueError` | 当 `extension` 为 null 或空字符串时抛出。 |

### 示例

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### 另见
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
