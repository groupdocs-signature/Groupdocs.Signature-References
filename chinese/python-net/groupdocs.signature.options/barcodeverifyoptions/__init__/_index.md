---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "初始化条形码签名的默认验证选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化条形码签名的默认验证选项。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

使用验证文本初始化默认验证选项。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 要验证的条形码文本。 |

## __init__ {#encode_type}

使用条形码类型验证初始化默认验证选项。

```python
def __init__(self, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| encode_type | `BarcodeType` | 条形码类型验证。 |

## __init__ {#text-encode_type}

使用条形码类型验证和文本初始化默认验证选项。

```python
def __init__(self, text, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 要验证的条形码文本。 |
| encode_type | `BarcodeType` | 条形码类型验证。 |

### 另见
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
