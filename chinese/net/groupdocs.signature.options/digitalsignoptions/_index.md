---
title: "DigitalSignOptions"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示数字签名的选项。"
type: docs
weight: 1560
url: /zh/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

表示数字签名的选项。

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | 使用默认值初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | 使用证书流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | 使用证书文件初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | 使用证书流和图像流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | 使用证书流和图像文件初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | 使用证书文件和图像流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | 使用证书文件和图像文件初始化 DigitalSignOptions 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [AllowExpired](../../groupdocs.signature.options/digitalsignoptions/allowexpired) { get; set; } | 获取或设置一个标志，允许使用已过期的证书进行签名。默认值为 false：使用已过期的证书签名会抛出 [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)，并且文档不会被签名。 |
| [AllowNotYetValid](../../groupdocs.signature.options/digitalsignoptions/allownotyetvalid) { get; set; } | 获取或设置一个标志，允许使用尚未生效的证书进行签名。默认值为 false：使用此类证书签名会抛出 [`GroupDocsSignatureException`](../../groupdocs.signature/groupdocssignatureexception)，并且文档不会被签名。 |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 在所有文档页面上放置签名。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观。 |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 指定边框设置 |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | 获取或设置数字证书文件路径。仅在未指定 CertificateStream 时使用此属性。 |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | 获取或设置数字证书流。如果指定了此属性，则始终使用它而不是 CertificateFilePath。 |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | 获取或设置签名联系人。 |
| [CustomSignHash](../../groupdocs.signature.options/digitalsignoptions/customsignhash) { get; set; } | 获取或设置自定义哈希签名函数，允许用户实现自己的数字签名逻辑。这使得可以使用外部证书进行签名，并支持不同的哈希算法。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型 [`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展。 |
| [HashAlgorithm](../../groupdocs.signature.options/signoptions/hashalgorithm) { get; set; } | 获取或设置用于加密操作的哈希算法。仅在 PDF 文件的数字签名中受支持。 |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 文档页面上签名的高度，以度量值表示（像素、百分比或毫米，请参阅 [`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType）。 |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐方式。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 获取或设置签名图像文件路径。如果未指定 ImageStream，则仅使用此属性。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 获取或设置签名图像流。如果指定了此属性，则始终使用它而不是 ImageFilePath。 |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 签名在文档页上的左 X 位置，使用度量值（像素、百分比或毫米，参见 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType）。(如果未指定水平对齐，则有效)。 |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | 获取或设置签名位置。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | 左侧和顶部属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 获取或设置签名与文档边缘之间的间距。(仅在指定水平或垂直对齐时有效)。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的度量类型（像素、百分比或毫米）。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。最小值和默认值为 1。 |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 指定要签名的页面的选项。 |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | 获取或设置数字证书的密码。 |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | 获取或设置签名原因。 |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 在文档上放置图像的矩形区域。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 签名在文档页上的旋转角度（顺时针）。 |
| [ShapePosition](../../groupdocs.signature.options/imagesignoptions/shapeposition) { get; set; } | 定义形状在文档布局中应呈现的位置。仅适用于 Word 文档。 |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | 获取或设置文档数字签名的属性。对于签署 Pdf 文档，可以通过使用 [`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) 实例来设置高级属性。 |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的度量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 文档页面的拉伸模式。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 签名在文档页上的顶部 Y 位置，使用度量值（像素、百分比或毫米，参见 [`MeasureType`](../../groupdocs.signature.domain/measuretype) LocationMeasureType）。(如果未指定垂直对齐，则有效)。 |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 获取或设置签名透明度（值范围为 0.0（不透明）至 1.0（透明））。默认值为 0（不透明）。 |
| [UseLtv](../../groupdocs.signature.options/digitalsignoptions/useltv) { get; set; } | 获取/设置 ltv（长期验证）验证标志。 |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 签名在文档页上的垂直对齐方式。 |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | 获取或设置签名的可见性。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 签名在文档页上的宽度，使用度量值（像素、百分比或毫米，[`MeasureType`](../../groupdocs.signature.domain/measuretype) SizeMeasureType）。 |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES 类型 [`XAdESType`](./xadestype)。默认值为 None（XAdES 已关闭）。目前 XAdES 签名类型仅在 Spreadsheet 文档中受支持。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 顺序位置。决定重叠签名的显示顺序。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 清除内部资源 |

### 备注

**Learn more**

* Basic usage of creating Digital electronic signature by GroupDocs.Signature: [How to eSign document with Digital signature](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* Advanced usage of settings of Digital electronic signature with GroupDocs.Signature: [Advanced usage to eSign document with Digital signature and additional settings](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### 另请参见

* class [ImageSignOptions](../imagesignoptions)
* namespace [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
