---
title: "FormFieldSignOptions"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示 PDF 文档的 FormField 签名选项类。"
type: docs
weight: 1600
url: /zh/net/groupdocs.signature.options/formfieldsignoptions/
---
## FormFieldSignOptions class

表示 PDF 文档的 FormField 签名选项类。

```csharp
public sealed class FormFieldSignOptions : TextSignOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [FormFieldSignOptions](formfieldsignoptions#constructor)() | 使用默认值初始化 PdfFormFieldSignOptions 类的新实例。 |
| [FormFieldSignOptions](formfieldsignoptions#constructor_1)(FormFieldSignature) | 使用 FormField 签名初始化 PdfFormFieldSignOptions 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文档页面上放置签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 获取或设置签名的背景设置。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 指定边框设置 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 获取或设置签名的字体。 |
| virtual [ForeColor](../../groupdocs.signature.options/textsignoptions/forecolor) { get; set; } | 获取或设置签名的前景颜色。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 获取或设置文本表单字段的标题，以将文本签名放入其中。此属性只能在 SignatureImplementation = TextToFormField 时使用。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 获取或设置用于放置文本签名的表单字段类型。此属性只能在 SignatureImplementation = TextToFormField 时使用。默认值为 AllTextTypes。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 获取或设置用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 文档页面上签名的高度，以测量值表示（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType 属性）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐方式。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 签名在文档页上的左侧 X 位置，使用测量值（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType 属性）。(如果未指定水平对齐，则有效)。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 获取或设置本机属性。如果设置了该属性，可使用文档特定的签名。例如，WordProcessing 文档的本机文本水印不同于常规水印。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。最小值和默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 指定要签名的页面的选项。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 签名在文档页上的旋转角度（顺时针）。 |
| [ShapePosition](../../groupdocs.signature.options/textsignoptions/shapeposition) { get; set; } | 定义形状在文档布局中应呈现的位置。仅适用于 Word 文档。 |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 获取或设置放置文本的形状类型。此属性只能在 SignatureImplementation = TextStamp 时使用。默认值为 Rectangle。 |
| [Signature](../../groupdocs.signature.options/formfieldsignoptions/signature) { get; set; } | 获取或设置签名的 FormField。 |
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

* Basic usage of creating FormField electronic signature by GroupDocs.Signature: [How to eSign document with FormField signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Form+Field+signature)
* Advanced usage of settings of FormField electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with FormField signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Form+Field+signature+-+advanced)

### 另请参见

* class [TextSignOptions](../textsignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
