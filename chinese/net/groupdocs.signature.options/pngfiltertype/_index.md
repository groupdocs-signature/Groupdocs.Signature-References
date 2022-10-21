---
title: PngFilterType
second_title: GroupDocs.Signature for .NET API 参考
description: 表示 PNG 图片滤镜类型
type: docs
weight: 1470
url: /zh/net/groupdocs.signature.options/pngfiltertype/
---
## PngFilterType enumeration

表示 PNG 图片滤镜类型。

```csharp
public enum PngFilterType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| None | `0` | 空过滤器，意味着不对图像数据行进行过滤。 |
| Sub | `1` | 子过滤器，意味着减法过滤将应用于图像数据。 |
| Up | `2` | 上过滤器，意味着将应用逐行减法过滤器。 |
| Avg | `3` | avg 过滤器意味着，该平均过滤器将应用于图像数据。 |
| Paeth | `4` | 路径预测器过滤器。 |
| Adaptive | `5` | 自适应过滤，意味着保存过程会为每个数据行选择最合适的filter 。最好的压缩，最慢的执行时间。 |

### 也可以看看

* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->