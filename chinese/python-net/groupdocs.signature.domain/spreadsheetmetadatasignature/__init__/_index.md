---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用预定义的名称和空值初始化 Spreadsheet Metadata Signature。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

使用预定义的名称和空值初始化 Spreadsheet Metadata Signature。

```python
def __init__(self, name):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 电子表格元数据签名的名称。 |

## __init__ {#name-value}

使用预定义的值初始化 Spreadsheet Metadata Signature。

```python
def __init__(self, name, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| name | `str` | 元数据签名对象的名称。 |
| value | `Any` | 元数据签名的值。 |

### 示例

```python
from datetime import datetime
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# 为电子表格创建元数据签名
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### 另见
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
