---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 QRCodeSearchOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 QRCodeSearchOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

使用编码类型值初始化 QRCodeSearchOptions 类的新实例。

```python
def __init__(self, encode_type):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| encode_type | `QrCodeType` | 指定 QR-Code 编码类型。 |

## __init__ {#encode_type-text}

使用编码类型和文本值初始化 QRCodeSearchOptions 类的新实例。

```python
def __init__(self, encode_type, text):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| encode_type | `QrCodeType` | 指定 QR-Code 编码类型。 |
| text | `str` | 设置 QR-Code 签名的文本。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### 另见
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
