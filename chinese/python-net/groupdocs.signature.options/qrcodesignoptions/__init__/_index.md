---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 QRCodeSignOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 QRCodeSignOptions 类的新实例。

```python
def __init__(self):
    ...
```

## __init__ {#text}

使用指定的文本初始化 QR 码签名选项实例。

```python
def __init__(self, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 签名文本。 |

### 示例

```python
from groupdocs.signature.options import QrCodeSignOptions

# 使用所需文本创建二维码签名选项
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

使用文本初始化 QrCodeSignOptions 类的新实例。

```python
def __init__(self, text, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | `str` | 二维码文本。 |
| encode_type | `QrCodeType` | 二维码编码类型。 |

### 示例

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### 另见
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
