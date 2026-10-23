---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "初始化 QR-Code 签名的验证选项。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

初始化 QR-Code 签名的验证选项。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

使用指定的 QR 码文本初始化 QR-Code 签名的验证选项。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 用于验证的 QR 码文本。 |

### 示例

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# 创建选项并设置用于验证的 QR 码文本
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

使用文本和 QR-Code 编码类型初始化 QR-Code 签名的验证选项。

```python
def __init__(self, text, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 待验证的文本。 |
| encode_type | `QrCodeType` | 编码类型。 |

### 示例

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### 另见
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
