---
title: "GroupDocs.Signature.Domain"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "此命名空间提供用于处理文档表示的类。"
type: docs
weight: 20
url: /zh/net/groupdocs.signature.domain/
---
此命名空间提供用于处理文档表示的类。

## 类

| 类 | 描述 |
| --- | --- |
| [Background](./background) | 表示背景外观 |
| [BarcodeSignature](./barcodesignature) | 包含条形码签名属性。 |
| [BarcodeType](./barcodetype) | 指定条形码类型属性。 |
| [BarcodeTypes](./barcodetypes) | 条形码类型容器。 |
| [BaseSignature](./basesignature) | 描述签名的基类。 |
| [Border](./border) | 表示边框外观 |
| [CertificateMetadataSignature](./certificatemetadatasignature) | 包含证书元数据签名属性。 |
| [CheckboxFormFieldSignature](./checkboxformfieldsignature) | 包含复选框输入表单字段签名属性。 |
| [ComboboxFormFieldSignature](./comboboxformfieldsignature) | 包含下拉框输入表单字段签名属性。 |
| [Corners](./corners) | 表示正方形图形对象的角。 |
| [DeleteResult](./deleteresult) | 文档中签名删除的结果。 |
| [DigitalFormFieldSignature](./digitalformfieldsignature) | 包含 PDF 文档的数字签名输入表单字段属性。 |
| [DigitalSignature](./digitalsignature) | 包含数字签名属性。 |
| [DocumentInfo](./documentinfo) | 定义文档描述属性。 |
| [DocumentResultSignature](./documentresultsignature) | 对包含新创建签名的文档进行归档签名处理后的结果。 |
| [FileType](./filetype) | 表示文件类型。 |
| [FormFieldSignature](./formfieldsignature) | 包含表单字段签名属性。 |
| [ImageMetadataSignature](./imagemetadatasignature) | 包含图像元数据签名属性。 |
| [ImageSignature](./imagesignature) | 包含图像签名属性。 |
| [MetadataSignature](./metadatasignature) | 包含元数据签名属性。 |
| [MetadataSignatureCollection](./metadatasignaturecollection) | 元数据签名对象的集合。 |
| [Padding](./padding) | 表示与元素关联的填充或边距信息。 |
| [PageInfo](./pageinfo) | 文档页面描述类 |
| [PdfDigitalSignature](./pdfdigitalsignature) | 包含 PDF 数字签名属性。 |
| [PdfMetadataSignature](./pdfmetadatasignature) | 包含 PDF 元数据签名属性。 |
| [PdfMetadataSignatures](./pdfmetadatasignatures) | 包含用于 PDF 文档元数据签名选项的标准元数据签名。 |
| [PresentationMetadataSignature](./presentationmetadatasignature) | 包含演示元数据签名属性。 |
| [ProcessLog](./processlog) | 表示文档处理细节。 |
| [QrCodeSignature](./qrcodesignature) | 包含二维码签名属性。 |
| [QrCodeType](./qrcodetype) | 指定 QRCode 类型属性。 |
| [QrCodeTypes](./qrcodetypes) | QRCode 类型容器。 |
| [RadioButtonFormFieldSignature](./radiobuttonformfieldsignature) | 包含单选按钮输入表单字段签名属性。 |
| [SearchResult](./searchresult) | 在指定文档中搜索签名的结果。 |
| [SignatureFont](./signaturefont) | 创建 SignatureFont 类的实例以指定 Font 属性。 |
| [SignResult](./signresult) | 对文档使用新创建的签名进行签名过程的结果。 |
| [SpreadsheetMetadataSignature](./spreadsheetmetadatasignature) | 包含 Spreadsheet Metadata Signature 属性。 |
| [SquareBorder](./squareborder) | 用于保存方形印章线的 Border 线属性的实例。 |
| [StampLine](./stampline) | 指定印章线属性。 |
| [StampType](./stamptype) | 指定印章类型属性。 |
| [StampTypes](./stamptypes) | 印章类型容器。 |
| [TextFormFieldSignature](./textformfieldsignature) | 包含 Pdf 文档的文本输入表单字段签名属性。 |
| [TextSignature](./textsignature) | 包含文本签名属性。 |
| [UpdateResult](./updateresult) | 文档中签名修改的结果。 |
| [VerificationResult](./verificationresult) | 用于保存验证过程结果的实例。 |
| [WordProcessingMetadataSignature](./wordprocessingmetadatasignature) | 包含 WordProcessing 元数据签名属性。 |
## Structures

| 结构 | 描述 |
| --- | --- |
| [TimeStamp](./timestamp) | 表示从第三方站点获取时间戳的数据。 |
## 接口

| 接口 | 描述 |
| --- | --- |
| [IAlignment](./ialignment) | 描述文档页面上签名区域的对齐方式。 |
| [IDocumentInfo](./idocumentinfo) | 定义文档描述属性。 |
| [IRectangle](./irectangle) | 定义文档页面上签名区域的接口属性。 |
| [IResult](./iresult) | 签名过程结果的通用接口。 |
| [IRotation](./irotation) | 定义签名旋转的属性。 |
| [ITextAlignment](./itextalignment) | 定义文本签名中文本的对齐属性。 |
| [ITransparency](./itransparency) | 为不同对象的外观定义透明度属性 |
## 枚举

| 枚举 | 描述 |
| --- | --- |
| [CodeTextAlignment](./codetextalignment) | 条形码和 QR 码的代码文本对齐方式。 |
| [DashStyle](./dashstyle) | 表示文档上虚线绘制线条的样式。 |
| [DocumentType](./documenttype) | 定义文档类型。 |
| [FormFieldType](./formfieldtype) | 指定表单字段类型。 |
| [FormTextFieldType](./formtextfieldtype) | 定义 WordsProcessing 文档表单字段的文本类型。 |
| [HashAlgorithm](./hashalgorithm) | 指定用于加密签名的哈希算法。 |
| [HorizontalAlignment](./horizontalalignment) | 指定元素在文档页面上的水平对齐方式。 |
| [ImageSaveFileFormat](./imagesavefileformat) | 定义不同的保存文件格式。 |
| [MeasureType](./measuretype) | 指定文档页面上签名的度量单位。 |
| [MetadataType](./metadatatype) | 指定值的受支持元数据签名数据类型。 |
| [OoxmlCompliance](./ooxmlcompliance) | 指定 WordProcessing 文档的 OOXML 合规级别。保存时设置则覆盖原始文档的合规性；否则在保存时保留加载的文档合规性。 |
| [PdfDigitalSignatureType](./pdfdigitalsignaturetype) | 描述 PDF 数字签名类型的枚举。 |
| [PdfSaveFileFormat](./pdfsavefileformat) | 定义不同的保存文件格式。 |
| [PdfTextAnnotationBorderEffect](./pdftextannotationbordereffect) | 描述应应用于 PDF 文本注释边框的效果。 |
| [PdfTextStickerIcon](./pdftextstickericon) | 描述 PDF 文本注释贴纸图标外观的枚举。 |
| [PdfTextStickerState](./pdftextstickerstate) | 描述 PDF 文本注释贴纸状态的枚举。 |
| [PresentationSaveFileFormat](./presentationsavefileformat) | 定义不同的保存文件格式。 |
| [ProcessStatus](./processstatus) | 指定签名和验证过程的状态。 |
| [ProcessType](./processtype) | 定义对文档支持的过程，如 Info、Preview、Sign、Verify、Search、Update、Delete。 |
| [ShapePosition](./shapeposition) | 指定形状在文档布局中的位置。 |
| [SignatureType](./signaturetype) | 定义各种过程（如 Sign、Verify、Search、Update、Delete）支持的签名类型。 |
| [SpreadsheetSaveFileFormat](./spreadsheetsavefileformat) | 定义 Spreadsheet 文档的不同保存格式。 |
| [StampBackgroundCropType](./stampbackgroundcroptype) | 指定 Stamp 元素背景层的裁剪类型。 |
| [StampTextRepeatType](./stamptextrepeattype) | 指定印章线条的文本重复类型。 |
| [StretchMode](./stretchmode) | 表示文档页面上签名区域的拉伸模式。 |
| [TextHorizontalAlignment](./texthorizontalalignment) | 指定签名内部文本的水平对齐方式。 |
| [TextMatchType](./textmatchtype) | 指定字符串中文本匹配的类型。 |
| [TextShapeType](./textshapetype) | 指定文本形状的类型。 |
| [TextSignatureImplementation](./textsignatureimplementation) | 指定 PDF 文本签名的实现类型。 |
| [TextVerticalAlignment](./textverticalalignment) | 指定签名内部文本的垂直对齐方式。 |
| [VerticalAlignment](./verticalalignment) | 指定文档页面上元素的垂直对齐方式。 |
| [WordProcessingSaveFileFormat](./wordprocessingsavefileformat) | 定义 WordProcessing 文档的不同保存文件格式。 |
| [WordProcessingTextSignatureImplementation](./wordprocessingtextsignatureimplementation) | 指定 WordProcessing 文档中文本签名的实现类型。 |
| [XAdESType](./xadestype) | XML 高级电子签名 (XAdES) 的类型。 |

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
