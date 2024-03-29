---
title: PngColorType
second_title: GroupDocs.Signature for .NET API 参考
description: 代表PNG图片颜色类型
type: docs
weight: 1540
url: /zh/net/groupdocs.signature.options/pngcolortype/
---
## PngColorType enumeration

代表PNG图片颜色类型。

```csharp
[Flags]
public enum PngColorType
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Grayscale | `0` | 表示每个像素都是灰度样本的颜色类型。 |
| Truecolor | `2` | 表示每个像素都是 R、G、B 三元组的颜色类型。 |
| IndexedColor | `3` | 表示颜色类型，其中每个像素是一个调色板索引；应出现 PLTE 块 . |
| GrayscaleWithAlpha | `4` | 表示颜色类型，其中每个像素都是灰度样本，后跟 和 alpha 样本。 |
| TruecolorWithAlpha | `6` | 表示颜色类型，其中每个像素都是 R、G、B 三元组，后跟 alpha 样本。 |

### 也可以看看

* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
