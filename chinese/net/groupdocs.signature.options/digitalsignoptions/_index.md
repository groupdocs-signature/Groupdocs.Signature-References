---
title: DigitalSignOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 代表数字签名选项
type: docs
weight: 1340
url: /zh/net/groupdocs.signature.options/digitalsignoptions/
---
## DigitalSignOptions class

代表数字签名选项。

```csharp
public class DigitalSignOptions : ImageSignOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DigitalSignOptions](digitalsignoptions#constructor)() | 使用默认值初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_1)(Stream) | 使用证书流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_4)(string) | 使用证书文件初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_2)(Stream, Stream) | 使用证书流和图像流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_3)(Stream, string) | 使用证书流和图像文件初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_5)(string, Stream) | 使用证书文件和图像流初始化 DigitalSignOptions 类的新实例。 |
| [DigitalSignOptions](digitalsignoptions#constructor_6)(string, string) | 使用证书文件和图像文件初始化 DigitalSignOptions 类的新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [AllPages](../../groupdocs.signature.options/imagesignoptions/allpages) { get; set; } | 在所有文档页面上签名。 此属性只能用于多帧图像格式 (Tiff)。 |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 附加签名外观. |
| [Border](../../groupdocs.signature.options/imagesignoptions/border) { get; set; } | 指定边框设置 |
| [CertificateFilePath](../../groupdocs.signature.options/digitalsignoptions/certificatefilepath) { get; set; } | 获取或设置数字证书文件路径。 只有在未指定 CertificateStream 时才使用此属性。 |
| [CertificateStream](../../groupdocs.signature.options/digitalsignoptions/certificatestream) { get; set; } | 获取或设置数字证书流。 如果指定此属性，则始终使用它代替 CertificateFilePath. |
| [Contact](../../groupdocs.signature.options/digitalsignoptions/contact) { get; set; } | 获取或设置签名联系人。 |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 获取或设置签名选项的文档类型[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 签名扩展. |
| [Height](../../groupdocs.signature.options/imagesignoptions/height) { get; set; } | 签名在文档页面上的高度，以测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [HorizontalAlignment](../../groupdocs.signature.options/imagesignoptions/horizontalalignment) { get; set; } | 签名在文档页面上的水平对齐。 |
| [ImageFilePath](../../groupdocs.signature.options/imagesignoptions/imagefilepath) { get; set; } | 获取或设置签名图片文件路径。 仅在不指定ImageStream时使用该属性。 |
| [ImageStream](../../groupdocs.signature.options/imagesignoptions/imagestream) { get; set; } | 获取或设置签名图像流。 如果指定此属性，则始终使用它代替 ImageFilePath. |
| virtual [Left](../../groupdocs.signature.options/imagesignoptions/left) { get; set; } | 文档页面上签名的左侧 X 位置测量值 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定水平对齐则有效）. |
| [Location](../../groupdocs.signature.options/digitalsignoptions/location) { get; set; } | 获取或设置签名位置。 |
| virtual [LocationMeasureType](../../groupdocs.signature.options/imagesignoptions/locationmeasuretype) { get; set; } | Left 和 Top 属性的测量类型（像素、百分比或毫米）。 |
| virtual [Margin](../../groupdocs.signature.options/imagesignoptions/margin) { get; set; } | 获取或设置 Sign 和 Document 边缘之间的空间。 （仅在指定水平或垂直对齐时有效）。 |
| virtual [MarginMeasureType](../../groupdocs.signature.options/imagesignoptions/marginmeasuretype) { get; set; } | 获取或设置边距的测量类型（像素、百分比或毫米）。 |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 获取或设置用于签名的文档页码。 最小值，默认值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 用于指定要签名的页面的选项。 |
| [Password](../../groupdocs.signature.options/digitalsignoptions/password) { get; set; } | 获取或设置数字证书密码。 |
| [Reason](../../groupdocs.signature.options/digitalsignoptions/reason) { get; set; } | 获取或设置签名原因. |
| [Rectangle](../../groupdocs.signature.options/imagesignoptions/rectangle) { get; } | 将图像放在文档上的区域矩形。 |
| [RotationAngle](../../groupdocs.signature.options/imagesignoptions/rotationangle) { get; set; } | 文档页上签名的旋转角度（顺时针）. |
| [Signature](../../groupdocs.signature.options/digitalsignoptions/signature) { get; set; } | 获取或设置文档数字签名的属性。 对于签署 Pdf 文档，可以通过使用实例来设置高级属性[`PdfDigitalSignature`](../../groupdocs.signature.domain/pdfdigitalsignature) |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 获取签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| virtual [SizeMeasureType](../../groupdocs.signature.options/imagesignoptions/sizemeasuretype) { get; set; } | 宽度和高度属性的测量类型（像素、百分比或毫米）。 |
| [Stretch](../../groupdocs.signature.options/imagesignoptions/stretch) { get; set; } | 文档页面上的拉伸模式。 |
| virtual [Top](../../groupdocs.signature.options/imagesignoptions/top) { get; set; } | 文档页面上签名在测量值中的顶部 Y 位置 （像素、百分比或毫米见[`MeasureType`](../../groupdocs.signature.domain/measuretype)LocationMeasureType). （如果未指定垂直对齐则有效）. |
| [Transparency](../../groupdocs.signature.options/imagesignoptions/transparency) { get; set; } | 获取或设置签名透明度（值从 0.0（不透明）到 1.0（透明））。默认值为 0（不透明）. |
| [VerticalAlignment](../../groupdocs.signature.options/imagesignoptions/verticalalignment) { get; set; } | 签名在文档页面上的垂直对齐方式。 |
| [Visible](../../groupdocs.signature.options/digitalsignoptions/visible) { get; set; } | 获取或设置签名的可见性。 |
| [Width](../../groupdocs.signature.options/imagesignoptions/width) { get; set; } | 签名在文档页面上的宽度，测量值 （像素、百分比或毫米[`MeasureType`](../../groupdocs.signature.domain/measuretype)SizeMeasureType). |
| [XAdESType](../../groupdocs.signature.options/digitalsignoptions/xadestype) { get; set; } | XAdES 类型[`XAdESType`](./xadestype).默认值为无（XAdES 已关闭）。 目前仅电子表格文档支持 XAdES 签名类型。 |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 获取或设置文本签名的 Z 序位置。 确定重叠签名的显示顺序。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Dispose](../../groupdocs.signature.options/imagesignoptions/dispose)() | 清除内部资源 |

### 评论

**了解更多**

* GroupDocs.Signature创建数字电子签名的基本用法： [如何使用数字签名对文档进行电子签名](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Digital+signature)
* GroupDocs.Signature 数字电子签名设置的高级用法： [使用数字签名和其他设置对 eSign 文档进行高级使用](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Digital+signature+-+advanced)

### 也可以看看

* class [ImageSignOptions](../imagesignoptions)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
