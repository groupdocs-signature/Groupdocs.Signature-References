---
title: StampSignOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 表示 Stamp 签名选项
type: docs
weight: 1630
url: /zh/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

表示 Stamp 签名选项。

```csharp
public class StampSignOptions : ImageSignOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | 使用默认值初始化 StampSignOptions 类的新实例。 |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | 使用对齐选项初始化 StampSignOptions 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | 在所有文档页面上签名。 此属性只能用于多帧图像格式（Tiff）。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | 获取或设置图章背景。 |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | 获取或设置签名的背景颜色裁剪类型。 |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | 获取或设置签名的背景图片裁剪类型。 |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 指定边框设置 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 文档页面上签名的高度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 文档页面上签名的水平对齐方式。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 获取或设置签名图像文件路径。 仅当未指定 ImageStream 时才使用此属性。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 获取或设置签名图像流。 如果指定此属性，则始终使用它来代替 ImageFilePath。 |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | 呈现为一组矩形的内线列表。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 文档页面上签名的左 X 位置，测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定水平对齐方式则有效）. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 获取或设置符号和文档边缘之间的空间。 （仅在指定水平或垂直对齐时有效）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 获取或设置 Margin. 的度量类型（像素、百分比或毫米） |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | 渲染为同心圆的外线列表。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。 最小值，默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 用于指定要签名的页面的选项。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 将图像放在文档上的矩形区域。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 文档页面上签名的旋转角度（顺时针）。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | 获取或设置戳记类型。 默认值为Round。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 文档页面上的拉伸模式。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 文档页面上签名的顶部 Y 位置以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定垂直对齐方式则有效）. |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 获取或设置签名透明度（值从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 文档页面上签名的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 文档页面上签名的宽度，以测量值 （像素、百分比或毫米[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的Z-order位置。 确定重叠签名的显示顺序。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 清除内部资源 |

### 评论

**学到更多**

* GroupDocs.Signature创建Stamp电子签名的基本用法： [如何使用邮票签名对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* 使用 GroupDocs.Signature 设置 Stamp 电子签名的高级用法： [带有图章签名和其他设置的电子签名文档的高级用法](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### 也可以看看

* class [ImageSignOptions](../imagesignoptions)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
