---
title: "get_supported_file_types メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "サポートされているファイルタイプを取得します。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

サポートされているファイルタイプを取得します。

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### 例

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### 関連項目
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
