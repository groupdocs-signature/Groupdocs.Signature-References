---
title: "__init__ 构造函数"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用指定的标识符和数值初始化图像元数据签名。"
type: docs
url: /zh/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

使用指定的标识符和数值初始化图像元数据签名。

```python
def __init__(self, id, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata 签名的唯一标识符。请参阅 EXIF 标签规范的参考，以获取可能的 id 值。 |
| value | `Any` | 元数据值。 |

### 示例

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### 另见
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
