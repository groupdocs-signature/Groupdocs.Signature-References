---
title: "StampSignOptions"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示印章签名选项。"
type: docs
weight: 2000
url: /zh/net/groupdocs.signature.options/stampsignoptions/
---
## StampSignOptions class

表示印章签名选项。

```csharp
public class StampSignOptions : ImageSignOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [StampSignOptions](stampsignoptions#constructor)() | 使用默认值初始化 StampSignOptions 类的新实例。 |
| [StampSignOptions](stampsignoptions#constructor_1)(int, int, int, int) | 使用对齐选项初始化 StampSignOptions 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文档页面上放置签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Background](../../groupdocs.signature.options/stampsignoptions/background) { get; set; } | 获取或设置印章背景。 |
| [BackgroundColorCropType](../../groupdocs.signature.options/stampsignoptions/backgroundcolorcroptype) { get; set; } | 获取或设置签名的背景颜色裁剪类型。 |
| [BackgroundImageCropType](../../groupdocs.signature.options/stampsignoptions/backgroundimagecroptype) { get; set; } | 获取或设置签名的背景图像裁剪类型。 |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 指定边框设置 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 获取或设置用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。 |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 文档页面上签名的高度，以度量值表示（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐方式。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 获取或设置签名图像文件路径。如果未指定 ImageStream，则仅使用此属性。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 获取或设置签名图像流。如果指定了此属性，则始终使用它而不是 ImageFilePath。 |
| [InnerLines](../../groupdocs.signature.options/stampsignoptions/innerlines) { get; } | 内部线条列表，以矩形集合的形式呈现。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 签名在文档页上的左 X 位置，使用度量值（像素、百分比或毫米，参见 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType）。(如果未指定水平对齐，则有效)。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| [OuterLines](../../groupdocs.signature.options/stampsignoptions/outerlines) { get; } | 外部线条列表，以同心圆的形式呈现。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。最小值和默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 指定要签名的页面的选项。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 在文档上放置图像的矩形区域。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 签名在文档页上的旋转角度（顺时针）。 |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 定义形状在文档布局中应呈现的位置。仅适用于 Word 文档。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的度量类型（像素、百分比或毫米）。 |
| [StampType](../../groupdocs.signature.options/stampsignoptions/stamptype) { get; set; } | 获取或设置印章类型。默认值为圆形。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 文档页面的拉伸模式。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 签名在文档页上的顶部 Y 位置，使用度量值（像素、百分比或毫米，参见 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType）。(如果未指定垂直对齐，则有效)。 |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。默认值为 0（不透明）。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 签名在文档页上的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 签名在文档页上的宽度，使用度量值（像素、百分比或毫米，[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType）。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 顺序位置。决定重叠签名的显示顺序。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 清除内部资源 |

### 备注

**Learn more**

* Basic usage of creating Stamp electronic signature by GroupDocs.Signature: [How to eSign document with Stamp signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Stamp+signature)
* Advanced usage of settings of Stamp electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Stamp signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Stamp+signature+-+advanced)

### 另请参见

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
