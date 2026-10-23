---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 TextSearchOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 TextSearchOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # 使用默认选项搜索文本签名
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

使用文本值初始化 TextSearchOptions 类的新实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 文本签名的文本。 |

### 另见
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
