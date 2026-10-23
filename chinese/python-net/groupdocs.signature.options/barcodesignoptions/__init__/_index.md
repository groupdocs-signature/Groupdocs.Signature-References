---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 BarcodeSignOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 BarcodeSignOptions 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#text}

使用文本初始化 BarcodeSignOptions 类的新实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 条形码文本。 |

### 示例

```python
from groupdocs.signature.options import BarcodeSignOptions

# 使用所需文本创建条形码签名选项
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

使用文本初始化 BarcodeSignOptions 类的新实例。

```python
def __init__(self, text, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 条形码文本。 |
| encode_type | `BarcodeType` | 条形码编码类型。 |

### 示例

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# 使用文本和类型创建条形码签名选项
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### 另见
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
