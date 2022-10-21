---
title: QrCodeSignOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 代表二维码签名选项
type: docs
weight: 1550
url: /zh/net/groupdocs.signature.options/qrcodesignoptions/
---
## QrCodeSignOptions class

代表二维码签名选项。

```csharp
public class QrCodeSignOptions : TextSignOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [QrCodeSignOptions](qrcodesignoptions#constructor)() | 使用默认值初始化 QRCodeSignOptions 类的新实例。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_1)(string) | 使用文本初始化 QRCodeSignOptions 类的新实例。 |
| [QrCodeSignOptions](qrcodesignoptions#constructor_2)(string, QrCodeType) | 使用文本初始化 BarcodeSignOptions 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文档页面上签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Background](../../groupdocs.signature.options/textsignoptions/background) { get; set; } | 获取或设置签名背景设置。 |
| [Border](../../groupdocs.signature.options/textsignoptions/border) { get; set; } | 指定边框设置 |
| [CodeTextAlignment](../../groupdocs.signature.options/qrcodesignoptions/codetextalignment) { get; set; } | 获取或设置结果二维码图像中文本的对齐方式。 默认值为无。 |
| [Data](../../groupdocs.signature.options/qrcodesignoptions/data) { get; set; } | 获取或设置要序列化为二维码内容的自定义对象。 |
| [DataEncryption](../../groupdocs.signature.options/qrcodesignoptions/dataencryption) { get; set; } | 获取或设置的实现[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)用于编码和解码二维码签名文本或数据属性的接口。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [EncodeType](../../groupdocs.signature.options/qrcodesignoptions/encodetype) { get; set; } | 获取或设置二维码类型。 |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [Font](../../groupdocs.signature.options/textsignoptions/font) { get; set; } | 获取或设置签名字体。 |
| override [ForeColor](../../groupdocs.signature.options/qrcodesignoptions/forecolor) { get; set; } | 获取或设置二维码条的前景色 使用此属性可能会导致验证问题。小心使用它。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textsignoptions/formtextfieldtitle) { get; set; } | 获取或设置文本表单字段的标题以将文本签名放入其中。 此属性只能与 SignatureImplementation = TextToFormField 一起使用。 |
| [FormTextFieldType](../../groupdocs.signature.options/textsignoptions/formtextfieldtype) { get; set; } | 获取或设置表单字段的类型以将文本签名放入其中。 此属性只能与 SignatureImplementation = TextToFormField 一起使用。 默认值为 AllTextTypes。 |
| [Height](../../groupdocs.signature.options/textsignoptions/height) { get; set; } | 文档页面上签名的高度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType 属性). |
| [HorizontalAlignment](../../groupdocs.signature.options/textsignoptions/horizontalalignment) { get; set; } | 文档页面上签名的水平对齐方式。 |
| [InnerMargins](../../groupdocs.signature.options/qrcodesignoptions/innermargins) { get; set; } | 获取或设置二维码元素和结果图像边框之间的间距。 |
| [Left](../../groupdocs.signature.options/textsignoptions/left) { get; set; } | 文档页面上签名的左 X 位置，测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType 属性）. （如果未指定水平对齐方式则有效）. |
| virtual [LocationMeasureType](../../groupdocs.signature.options/textsignoptions/locationmeasuretype) { get; set; } | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| [LogoFilePath](../../groupdocs.signature.options/qrcodesignoptions/logofilepath) { get; set; } | 获取或设置 QR 码徽标图像文件名。 仅当未指定 LogoStream 时才使用此属性。 使用此属性可能会导致验证问题。小心使用它。 |
| [LogoStream](../../groupdocs.signature.options/qrcodesignoptions/logostream) { get; set; } | 获取或设置 QR 码徽标图像流。 如果指定此属性，则始终使用它代替 LogoFilePath。 使用此属性可能会导致验证问题。小心使用它。 |
| virtual [Margin](../../groupdocs.signature.options/textsignoptions/margin) { get; set; } | 获取或设置符号和文档边缘之间的空间。 （仅在指定水平或垂直对齐时有效）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/textsignoptions/marginmeasuretype) { get; set; } | 获取或设置 Margin. 的度量类型（像素、百分比或毫米） |
| [Native](../../groupdocs.signature.options/textsignoptions/native) { get; set; } | 获取或设置本机属性。如果已设置，则可以使用文档特定签名。 WordProcessing 文档的本机文本水印不同于常规，例如。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。 最小值，默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 用于指定要签名的页面的选项。 |
| [ReturnContent](../../groupdocs.signature.options/qrcodesignoptions/returncontent) { get; set; } | 获取或设置标志以获取放在文档页面上的签名的 QR-Code 图像内容。 如果此标志设置为 true，则 QR-Code 签名图像内容将按所需格式保存原始图像数据[`ReturnContentType`](./returncontenttype). 默认情况下禁用此选项。 |
| [ReturnContentType](../../groupdocs.signature.options/qrcodesignoptions/returncontenttype) { get; set; } | 指定启用 ReturnContent 属性时 QR 码签名的返回图像内容的文件类型。 默认设置为 Null。这意味着以原始格式返回 QR 码图像内容。 此图像格式指定于[`Format`](../../groupdocs.signature.domain/qrcodesignature/format) 可能支持的值为：FileType.JPEG、FileType.PNG、FileType.BMP。 如果不支持提供的格式，则将返回 .png 格式的二维码图像内容。 |
| [RotationAngle](../../groupdocs.signature.options/textsignoptions/rotationangle) { get; set; } | 文档页面上签名的旋转角度（顺时针）。 |
| [ShapeType](../../groupdocs.signature.options/textsignoptions/shapetype) { get; set; } | 获取或设置要放置文本的形状类型。 此属性只能与 SignatureImplementation = TextStamp 一起使用。 默认值为矩形。 |
| [SignatureID](../../groupdocs.signature.options/textsignoptions/signatureid) { get; set; } | 获取或设置签名的唯一标识。它可用于签名验证选项。 属性仅支持 Pdf 文档。 |
| [SignatureImplementation](../../groupdocs.signature.options/textsignoptions/signatureimplementation) { get; set; } | 获取或设置文本签名实现的类型。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/textsignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/textsignoptions/stretch) { get; set; } | 文档页面上的拉伸模式。 |
| [Text](../../groupdocs.signature.options/textsignoptions/text) { get; set; } | 获取或设置签名文本。 |
| [TextHorizontalAlignment](../../groupdocs.signature.options/textsignoptions/texthorizontalalignment) { get; set; } | 签名内文本的水平对齐。 仅图像和注释签名实现支持此功能 （请参阅[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation 属性）. |
| [TextVerticalAlignment](../../groupdocs.signature.options/textsignoptions/textverticalalignment) { get; set; } | 签名内文本的垂直对齐方式。 仅图像签名实现 支持此功能（请参阅[`TextSignatureImplementation`](../../groupdocs.signature.domain/textsignatureimplementation)SignatureImplementation 属性）。 |
| [Top](../../groupdocs.signature.options/textsignoptions/top) { get; set; } | 文档页面上签名的顶部 Y 位置以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType 属性）. （如果未指定垂直对齐方式则有效）. |
| [Transparency](../../groupdocs.signature.options/textsignoptions/transparency) { get; set; } | 获取或设置签名透明度（值从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）。 |
| [VerticalAlignment](../../groupdocs.signature.options/textsignoptions/verticalalignment) { get; set; } | 文档页面上签名的垂直对齐方式。 |
| [Width](../../groupdocs.signature.options/textsignoptions/width) { get; set; } | 文档页面上签名的宽度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType 属性). |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的Z-order位置。 确定重叠签名的显示顺序。 |

### 评论

**学到更多**

* GroupDocs创建二维码电子签名的基本用法。签名： [如何使用 QR 码签名对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+QR-code+signature)
* GroupDocs 二维码电子签名设置的高级用法。签名： [使用 QR 码签名和其他设置对 eSign 文档进行高级使用](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+QR-code+signature+-+advanced)

### 也可以看看

* class [TextSignOptions](../textsignoptions)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
