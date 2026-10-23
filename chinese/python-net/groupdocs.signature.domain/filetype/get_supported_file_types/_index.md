---
title: "get_supported_file_types 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "检索受支持的文件类型。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

检索受支持的文件类型。

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### 示例

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### 另见
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
