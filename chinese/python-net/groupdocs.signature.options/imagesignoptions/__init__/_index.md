---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用默认值初始化 ImageSignOptions 类的新实例。"
type: docs
url: /zh/python-net/groupdocs.signature.options/imagesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

使用默认值初始化 ImageSignOptions 类的新实例。

```python
def __init__(self):
    ...
```

### 示例

```python
from groupdocs.signature.options import ImageSignOptions

# 使用图像文件路径创建图像签名选项
options = ImageSignOptions("signature.jpg")
```

## __init__ {#image_file_path}

使用图像文件初始化 ImageSignOptions。

```python
def __init__(self, image_file_path):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_file_path | `str` | 图像文件路径。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    options = ImageSignOptions("signature.jpg")
    # 在此配置其他选项，例如位置、大小等。
    result = signature.sign("signed_image.pdf", options)
    print(f"Signed with {len(result.succeeded)} image signature(s)")
```

## __init__ {#image_stream}

使用图像流初始化新的 ImageSignOptions 实例。

```python
def __init__(self, image_stream):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_stream | `io.RawIOBase` | 图像流。 |

### 示例

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import ImageSignOptions

with Signature("sample.pdf") as signature:
    with open("signature.jpg", "rb") as image_stream:
        options = ImageSignOptions(image_stream)
        options.left = 100
        options.top = 400
        result = signature.sign("signed_image_stream.pdf", options)
        print(f"Signed with {len(result.succeeded)} image signature(s)")
```

### 另见
* class [`ImageSignOptions`](/signature/python-net/groupdocs.signature.options/imagesignoptions/)
