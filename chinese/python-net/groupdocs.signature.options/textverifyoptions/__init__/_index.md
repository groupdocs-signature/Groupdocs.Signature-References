---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 TextVerifyOptions 的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/textverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 TextVerifyOptions 的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

def verify_text_signature():
    with Signature("signed.pdf") as signature:
        options = TextVerifyOptions("John Smith")
        result = signature.verify(options)
        print(f"Document is signed by John Smith: {result.is_valid}")

if __name__ == "__main__":
    verify_text_signature()
```

## __init__ {#text}

使用验证文本初始化 TextVerifyOptions 的新实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 待验证的文本。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

## __init__ {#text-implementation}

使用待验证的文本和签名实现类型初始化新的 TextVerifyOptions 实例。

```python
def __init__(self, text, implementation):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 待验证的文本。 |
| implementation | `TextSignatureImplementation` | 签名实现类型。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextVerifyOptions

with Signature("signed.pdf") as signature:
    options = TextVerifyOptions("John Smith")
    result = signature.verify(options)
    print(f"Document is signed by John Smith: {result.is_valid}")
```

### 另见
* class [`TextVerifyOptions`](/signature/python-net/groupdocs.signature.options/textverifyoptions/)
