---
title: QrCodeVerifyOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 保留验证文档二维码签名的选项
type: docs
weight: 1640
url: /zh/net/groupdocs.signature.options/qrcodeverifyoptions/
---
## QrCodeVerifyOptions class

保留验证文档二维码签名的选项。

```csharp
public class QrCodeVerifyOptions : TextVerifyOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor)() | 为二维码签名创建验证选项 QrCodeVerifyOptions. |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_1)(string) | 为带有 QR 码文本的 QR 码签名创建验证选项 QrCodeVerifyOptions 以进行验证。 |
| [QrCodeVerifyOptions](qrcodeverifyoptions#constructor_2)(string, QrCodeType) | 为带有文本和 QR 码编码类型的 QR 码签名创建验证选项 QrCodeVerifyOptions 以进行验证。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | 标志以验证每个文档页面。默认值为 true. |
| [DataEncryption](../../groupdocs.signature.options/qrcodeverifyoptions/dataencryption) { get; set; } | 获取或设置的实现[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)编码和解码二维码签名文本属性的接口。 |
| [EncodeType](../../groupdocs.signature.options/qrcodeverifyoptions/encodetype) { get; set; } | 获取或设置二维码类型验证。此属性是可选的。 |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | 用于替代签名选项验证的附加扩展。 |
| [FormTextFieldTitle](../../groupdocs.signature.options/textverifyoptions/formtextfieldtitle) { get; set; } | 获取或设置表单字段的标题以验证它。 如果此属性设置文本将仅在文本表单字段中找到。 |
| [FormTextFieldType](../../groupdocs.signature.options/textverifyoptions/formtextfieldtype) { get; set; } | 获取或设置表单字段的类型以验证它。 如果此属性设置文本将仅在文本表单字段中找到。 |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | 有效属性标志。 |
| [MatchType](../../groupdocs.signature.options/textverifyoptions/matchtype) { get; set; } | 获取或设置文本匹配类型验证。 |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | 要验证的文档页码。如果未设置属性 - 文档的所有页面将在第一次出现时进行验证。 最小值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | 用于指定要验证的页面的页面选项。 |
| [SignatureID](../../groupdocs.signature.options/textverifyoptions/signatureid) { get; set; } | 如果应验证，请指定大于零的文本签名 ID。此属性仅支持 Pdf 文档 |
| [SignatureImplementation](../../groupdocs.signature.options/textverifyoptions/signatureimplementation) { get; set; } | 要验证的签名类型。 |
| [Text](../../groupdocs.signature.options/textverifyoptions/text) { get; set; } | 如果需要验证则指定签名文本。 |

### 评论

**了解更多**

* GroupDocs验证二维码电子签名的基本用法。Signature: [如何电子验证文档中的二维码签名](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures+in+the+document)
* GroupDocs.Signature: 二维码电子签名校验设置高级用法[文档中 eVerification QR 码签名的高级用法和其他设置](https://docs.groupdocs.com/display/signaturenet/Verify+QR-code+signatures)

### 也可以看看

* class [TextVerifyOptions](../textverifyoptions)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
