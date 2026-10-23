---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用证书文件初始化 DigitalVBA 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.domain.extensions/digitalvba/__init__/
is_root: false
weight: 10
---


## __init__ {#certificate_file_path-password}

使用证书文件初始化 DigitalVBA 类的新实例。

```python
def __init__(self, certificate_file_path, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_file_path | `str` | 数字证书文件路径。 |
| password | `str` | 数字证书密码。 |

### 示例

```python
from groupdocs.signature.domain.extensions import DigitalVBA

# 使用证书文件和密码创建 DigitalVBA 扩展
digital_vba = DigitalVBA("certificate.pfx", "1234567890")
```

## __init__ {#certificate_stream-password}

使用证书流初始化 DigitalVBA 类的新实例。

```python
def __init__(self, certificate_stream, password):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 包含数字证书的 io.RawIOBase。 |
| password | `str` | 数字证书的 str 密码。 |

### 另见
* class [`DigitalVBA`](/signature/python-net/groupdocs.signature.domain.extensions/digitalvba/)
