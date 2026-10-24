---
title: "from_extension メソッド"
second_title: "Python 用 .NET 経由の GroupDocs.Signature API リファレンス"
description: "ファイル拡張子をファイルタイプにマップします。"
type: docs
url: /ja/python-net/groupdocs.signature.domain/filetype/from_extension/
is_root: false
weight: 1040
---


## from_extension {#extension}

ファイル拡張子をファイルタイプにマップします。

```python
def from_extension(cls, extension):
    ...
```

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| extension | `str` | ファイル拡張子（ピリオド「.」を含む）。 |

**Returns:** FileType: When file type is supported returns it, otherwise returns default `FileType.unknown` file type.

| 例外 | 説明 |
| :- | :- |
| `ValueError` | `extension` が null または空文字列のときに発生します。 |

### 例

```python
import os
from groupdocs.signature.domain import FileType

extension = os.path.splitext("contract.pdf")[1]
if FileType.from_extension(extension) == FileType.UNKNOWN:
    print(f"{extension} files are not supported")
else:
    print(f"{extension} files are supported")
```

### 関連項目
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
