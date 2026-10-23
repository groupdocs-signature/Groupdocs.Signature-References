---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 DigitalVerifyOptions 实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 DigitalVerifyOptions 实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

with Signature("signed.pdf") as signature:
    options = DigitalVerifyOptions("certificate.pfx")
    options.password = "1234567890"
    result = signature.verify(options)
    print(f"Verification result: {result.is_valid}")
```

## __init__ {#certificate_file_path}

使用给定的数字证书文件路径初始化 DigitalVerifyOptions 实例。

```python
def __init__(self, certificate_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_file_path | `str` | 数字证书的文件路径。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalVerifyOptions

options = DigitalVerifyOptions("certificate.pfx")
options.password = "1234567890"
```

## __init__ {#certificate_stream}

使用给定的证书流初始化 DigitalVerifyOptions 实例。

```python
def __init__(self, certificate_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 证书的流。 |

### 另见
* class [`DigitalVerifyOptions`](/signature/python-net/groupdocs.signature.options/digitalverifyoptions/)
