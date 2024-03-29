---
title: BitmapCompression
second_title: GroupDocs.Signature for .NET API 参考
description: 指定不同的位图压缩方法
type: docs
weight: 1280
url: /zh/net/groupdocs.signature.options/bitmapcompression/
---
## BitmapCompression enumeration

指定不同的位图压缩方法。

```csharp
public enum BitmapCompression
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Rgb | `0` | 没有压缩。 |
| Rle8 | `1` | RLE 8 位/像素压缩。只能用于 8 位/像素位图。 |
| Rle4 | `2` | RLE 4 位/像素压缩。只能用于 4 位/像素位图。 |
| Bitfields | `3` | 位字段。只能用于 16 位和 32 位/像素位图。 |
| Jpeg | `4` | JPEG 压缩。位图包含 JPEG 图像。 |
| Png | `5` | PNG压缩。位图包含 PNG 图像。 |

### 也可以看看

* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
