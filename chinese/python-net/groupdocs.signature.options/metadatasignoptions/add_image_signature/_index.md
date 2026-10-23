---
title: "add_image_signature 方法"
second_title: "GroupDocs.Signature for Python via .NET API 参考"
description: "使用给定参数创建新的 ImageMetadataSignature 并将其添加到集合中。"
type: docs
url: /zh/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

使用给定参数创建新的 ImageMetadataSignature 并将其添加到集合中。

```python
def add_image_signature(self, id, value):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata Signature 名称的唯一标识符。请参阅 Exif 标签规范的参考，以获取可能的 id 值。 |
| value | `Any` | 元数据值。 |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### 另见
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
