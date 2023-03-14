---
title: ImageSignOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 代表Image签名选项
type: docs
weight: 1420
url: /zh/net/groupdocs.signature.options/imagesignoptions/
---
## ImageSignOptions class

代表Image签名选项。

```csharp
public class ImageSignOptions : SignOptions, IAlignment, IDisposable, IRectangle, IRotation, 
    ITransparency
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [ImageSignOptions](imagesignoptions#constructor)() | 使用默认值初始化 ImageSignOptions 类的新实例。 |
| [ImageSignOptions](imagesignoptions#constructor_1)(Stream) | 使用图像流初始化 ImageSignOptions 类的新实例。 |
| [ImageSignOptions](imagesignoptions#constructor_2)(string) | 使用图像文件初始化 ImageSignOptions 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | 在所有文档页面上签名。 此属性只能用于多帧图像格式 (Tiff)。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 指定边框设置 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 签名在文档页面上的高度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 获取或设置签名图片文件路径。 仅在不指定ImageStream时使用该属性。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 获取或设置签名图像流。 如果指定此属性，则始终使用它代替 ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 文档页面上签名的左侧 X 位置测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定水平对齐则有效）. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 获取或设置 Sign 和 Document 边缘之间的空间。 （仅在指定水平或垂直对齐时有效）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的测量类型（像素、百分比或毫米）。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。 最小值，默认值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 用于指定要签名的页面的选项。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 将图像放在文档上的区域矩形。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 文档页上签名的旋转角度（顺时针）. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 文档页面上的拉伸模式。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 文档页面上签名在测量值中的顶部 Y 位置 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定垂直对齐则有效）. |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 获取或设置签名透明度（值从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 签名在文档页面上的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 签名在文档页面上的宽度，测量值 （像素、百分比或毫米[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 序位置。 确定重叠签名的显示顺序。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [FromBase64](../../groupdocs.signature.options/imagesignoptions/frombase64)(string) | 使用来自 Base64. 的预定义图像创建 ImageSignOptions 类的新实例 |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 清除内部资源 |

### 评论

**了解更多**

* GroupDocs.Signature创建Image电子签名的基本用法： [如何使用图像签名对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Image+signature)
* GroupDocs.Signature: Image电子签名设置的高级用法[使用图像签名和其他设置对 eSign 文档进行高级使用](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Image+signature+-+advanced)

### 也可以看看

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
