---
title: TextSignOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 表示文本签名选项
type: docs
weight: 1730
url: /zh/net/groupdocs.signature.options/textsignoptions/
---
## TextSignOptions class

表示文本签名选项。

```csharp
public class TextSignOptions : SignOptions, IAlignment, IRectangle, IRotation, ITransparency
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [TextSignOptions](textsignoptions#constructor)() | 使用默认值初始化 TextSignOptions 类的新实例。 |
| [TextSignOptions](textsignoptions#constructor_1)(string) | 用文本初始化 TextSignOptions 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文件页上签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观. |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 获取或设置签名背景设置。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 指定边框设置 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展. |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 获取或设置签名字体。 |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | 获取或设置签名前景色。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 获取或设置文本表单字段的标题以将文本签名放入其中。 此属性只能与 SignatureImplementation = TextToFormField 一起使用。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 获取或设置表单字段的类型以将文本签名放入其中。 此属性只能与 SignatureImplementation = TextToFormField 一起使用。 默认值为 AllTextTypes. |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 签名在文档页面上的高度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType 属性). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 文档页面上签名的左侧 X 位置测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType 属性）. （如果未指定水平对齐则有效）. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 获取或设置 Sign 和 Document 边缘之间的空间。 （仅在指定水平或垂直对齐时有效）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的测量类型（像素、百分比或毫米）。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 获取或设置本机属性。如果已设置，则可以使用文档特定签名。 WordProcessing 文档的本机文本水印与常规不同，例如。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。 最小值，默认值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 用于指定要签名的页面的选项。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 文档页上签名的旋转角度（顺时针）. |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 获取或设置放置文本的形状类型。 此属性只能与 SignatureImplementation = TextStamp 一起使用。 默认值为矩形。 |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 获取或设置签名的唯一ID。它可以用于签名验证选项。 属性仅支持 Pdf 文档。 |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | 获取或设置文本签名实现的类型。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | 文档页面上的拉伸模式。 |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 获取或设置签名的文本。 |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 签名内文本的水平对齐。 此功能仅支持图像和注释签名实现 （请参阅[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation 属性). |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 签名内文本的垂直对齐。 此功能仅支持图像签名实现 （请参阅[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation 属性）。 |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 文档页面上签名在测量值中的顶部 Y 位置 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType 属性）. （如果未指定垂直对齐则有效）. |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 获取或设置签名透明度（值从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）. |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | 签名在文档页面上的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | 签名在文档页面上的宽度，测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType 属性). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 序位置。 确定重叠签名的显示顺序。 |

### 评论

**了解更多**

* GroupDocs.Signature: 创建文本电子签名的基本用法[如何使用文本签名对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Text+signature)
* GroupDocs.Signature: 文本电子签名设置的高级用法[使用文本签名和其他设置对 eSign 文档进行高级使用](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Text+signature+-+advanced)

### 也可以看看

* class [SignOptions](../signoptions)
* interface [IAlignment](../../groupdocs.signature.domain/ialignment)
* interface [IRectangle](../../groupdocs.signature.domain/irectangle)
* interface [IRotation](../../groupdocs.signature.domain/irotation)
* interface [ITransparency](../../groupdocs.signature.domain/itransparency)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
