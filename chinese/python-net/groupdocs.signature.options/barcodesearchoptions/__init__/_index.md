---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 BarcodeSearchOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 BarcodeSearchOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature.options import BarcodeSearchOptions

# 使用默认设置创建搜索选项对象
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

使用编码类型值初始化 BarcodeSearchOptions 类的新实例。

```python
def __init__(self, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 指定条形码编码类型。 |

## __init__ {#encode_type-text}

使用编码类型和文本值初始化 BarcodeSearchOptions 类的新实例。

```python
def __init__(self, encode_type, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 指定条形码编码类型。 |
| text | `str` | 设置条形码签名的文本。 |

### 另见
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
