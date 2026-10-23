---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 DigitalSignOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/digitalsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 DigitalSignOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    signature.sign("signed.pdf", options)
```

## __init__ {#certificate_file_path}

使用证书文件初始化新的 DigitalSignOptions 实例。

```python
def __init__(self, certificate_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_file_path | `str` | 数字证书文件路径。 |

### 示例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream}

使用证书流初始化新的 DigitalSignOptions 实例。

```python
def __init__(self, certificate_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 数字证书流。 |

### 示例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with open("certificate.pfx", "rb") as cert_stream:
        options = DigitalSignOptions(cert_stream)
        options.password = "1234567890"

        with Signature("sample.pdf") as signature:
            result = signature.sign("signed.pdf", options)
            print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_file_path-image_file_path}

使用证书文件和外观图像文件初始化 DigitalSignOptions 类的新实例。

```python
def __init__(self, certificate_file_path, image_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_file_path | `str` | 数字证书文件路径。 |
| image_file_path | `str` | 签名外观图像文件路径。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # 将证书和外观图像传递给构造函数
    options = DigitalSignOptions("certificate.pfx", "signature.jpg")
    options.password = "1234567890"
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

## __init__ {#certificate_file_path-appearence_image_stream}

使用证书文件和外观图像流初始化 DigitalSignOptions 的新实例。

```python
def __init__(self, certificate_file_path, appearence_image_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_file_path | `str` | 数字证书文件路径。 |
| appearence_image_stream | `io.RawIOBase` | 签名外观图像流。 |

### 示例

```python
    from groupdocs.signature import Signature
    from groupdocs.signature.options import DigitalSignOptions

    with Signature("sample.pdf") as signature:
        options = DigitalSignOptions("certificate.pfx", "signature.jpg")
        options.password = "1234567890"
        result = signature.sign("signed.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
    ```

## __init__ {#certificate_stream-image_file_path}

使用证书流和外观图像文件初始化 DigitalSignOptions 的新实例。

```python
def __init__(self, certificate_stream, image_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | io.RawIOBase。数字证书流。 |
| image_file_path | `str` | str。签名外观图像文件路径。 |

## __init__ {#certificate_stream-appearence_image_stream}

使用证书流和外观图像流初始化新的 DigitalSignOptions 实例。

```python
def __init__(self, certificate_stream, appearence_image_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| certificate_stream | `io.RawIOBase` | 数字证书流。 |
| appearence_image_stream | `io.RawIOBase` | 签名外观图像流。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import DigitalSignOptions

with Signature("sample.pdf") as signature:
    # 从流中加载证书和外观图像
    with open("certificate.pfx", "rb") as cert_stream, open("signature.jpg", "rb") as img_stream:
        options = DigitalSignOptions(cert_stream, img_stream)
        options.password = "1234567890"

        result = signature.sign("signed_output.pdf", options)
        print(f"Signed with {len(result.succeeded)} digital signature(s)")
```

### 另见
* class [`DigitalSignOptions`](/signature/python-net/groupdocs.signature.options/digitalsignoptions/)
