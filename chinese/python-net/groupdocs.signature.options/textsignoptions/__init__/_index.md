---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 TextSignOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 TextSignOptions 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#text}

使用文本初始化 TextSignOptions 类的新实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 签名文本。 |

### 示例

```python
from groupdocs.signature.options import TextSignOptions

# 使用所需的签名文本创建文本签名选项
options = TextSignOptions("John Smith")
```

### 另见
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
