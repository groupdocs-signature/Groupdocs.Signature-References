---
title: "BarcodeSignOptions"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示条形码签名的选项。"
type: docs
weight: 1450
url: /zh/net/groupdocs.signature.options/barcodesignoptions/
---
## BarcodeSignOptions class

表示条形码签名的选项。

```csharp
public class BarcodeSignOptions : TextSignOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [BarcodeSignOptions](barcodesignoptions#constructor)() | 使用默认值初始化 BarcodeSignOptions 类的新实例。 |
| [BarcodeSignOptions](barcodesignoptions#constructor_1)(string) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |
| [BarcodeSignOptions](barcodesignoptions#constructor_2)(string, BarcodeType) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文档页面上放置签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 获取或设置签名的背景设置。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 指定边框设置 |
| [CodeTextAlignment](../../groupdocs.signature.options/barcodesignoptions/codetextalignment) { get; set; } | 获取或设置结果条形码图像中文本的对齐方式。默认值为 None。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/barcodesignoptions/encodetype) { get; set; } | 获取或设置条形码类型。 |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 获取或设置签名的字体。 |
| override [ForeColor](../../groupdocs.signature.options/barcodesignoptions/forecolor) { get; set; } | 获取或设置条形码条的前景颜色。使用此属性可能导致验证问题，请谨慎使用。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 获取或设置文本表单字段的标题，以将文本签名放入其中。此属性只能在 SignatureImplementation = TextToFormField 时使用。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 获取或设置用于放置文本签名的表单字段类型。此属性只能在 SignatureImplementation = TextToFormField 时使用。默认值为 AllTextTypes。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 获取或设置用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 文档页面上签名的高度，以测量值表示（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 属性）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐方式。 |
| [InnerMargins](../../groupdocs.signature.options/barcodesignoptions/innermargins) { get; set; } | 获取或设置条形码元素与结果图像边框之间的间距。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 签名在文档页上的左侧 X 位置，使用测量值（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 属性）。(如果未指定水平对齐，则有效)。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 获取或设置本机属性。如果设置了该属性，可使用文档特定的签名。例如，WordProcessing 文档的本机文本水印不同于常规水印。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。最小值和默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 指定要签名的页面的选项。 |
| [ReturnContent](../../groupdocs.signature.options/barcodesignoptions/returncontent) { get; set; } | 获取或设置标志，以获取放置在文档页上的签名的条形码图像内容。如果此标志设置为 true，条形码签名图像内容将按所需格式 [`ReturnContentType`](./returncontenttype) 保留原始图像数据。默认情况下此选项为禁用。 |
| [ReturnContentType](../../groupdocs.signature.options/barcodesignoptions/returncontenttype) { get; set; } | 指定在启用 ReturnContent 属性时返回的条形码签名图像内容的文件类型。默认设置为 Null，这意味着返回原始格式的条形码图像内容。该图像格式在 [`Format`](../../groupdocs.signature.domain/barcodesignature/format) 中指定，可能支持的值有：FileType.JPEG、FileType.PNG、FileType.BMP。如果提供的格式不受支持，则返回 .png 格式的条形码图像内容。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 签名在文档页上的旋转角度（顺时针）。 |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | 定义形状在文档布局中应呈现的位置。仅适用于 Word 文档。 |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 获取或设置放置文本的形状类型。此属性只能在 SignatureImplementation = TextStamp 时使用。默认值为 Rectangle。 |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 获取或设置签名的唯一 ID。它可用于签名验证选项。此属性仅在 Pdf 文档中受支持。 |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | 获取或设置文本签名实现的类型。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的度量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | 文档页面的拉伸模式。 |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 获取或设置签名的文本。 |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 签名内部文本的水平对齐。此功能仅在 Image 和 Annotation 签名实现中受支持（参见 [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation 属性）。 |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 签名内部文本的垂直对齐。此功能仅在 Image 签名实现中受支持（参见 [`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation) SignatureImplementation 属性）。 |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 签名在文档页上的顶部 Y 位置，使用测量值（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 属性）。(如果未指定垂直对齐，则有效)。 |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。默认值为 0（不透明）。 |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | 签名在文档页上的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | 签名在文档页上的宽度，使用测量值（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 属性）。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 顺序位置。决定重叠签名的显示顺序。 |

### 备注

**Learn more**

* Basic usage of creating Barcode electronic signature by GroupDocs.Signature: [How to eSign document with Barcode signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Barcode+signature)
* Advanced usage of settings of Barcode electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Barcode signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Barcode+signature+and+additional+settings)

### 另请参见

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
