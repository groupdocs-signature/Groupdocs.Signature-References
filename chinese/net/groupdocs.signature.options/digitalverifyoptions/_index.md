---
title: DigitalVerifyOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 保留验证文档数字签名的选项
type: docs
weight: 1270
url: /zh/net/groupdocs.signature.options/digitalverifyoptions/
---
## DigitalVerifyOptions class

保留验证文档数字签名的选项。

```csharp
public class DigitalVerifyOptions : VerifyOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [DigitalVerifyOptions](digitalverifyoptions#constructor)() | 使用默认值创建数字验证选项。 |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_1)(Stream) | 使用给定的证书流创建数字验证选项。 |
| [DigitalVerifyOptions](digitalverifyoptions#constructor_2)(string) | 使用给定的数字证书文件路径创建数字验证选项。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | 标志以验证每个文档页面。默认值为真。 |
| [Certificate](../../groupdocs.signature.options/digitalverifyoptions/certificate) { get; } | 从证书文件路径或流中获取 X509Certificate2 证书。 |
| [CertificateFilePath](../../groupdocs.signature.options/digitalverifyoptions/certificatefilepath) { get; set; } | 数字证书的文件路径。 |
| [CertificateStream](../../groupdocs.signature.options/digitalverifyoptions/certificatestream) { get; set; } | 数字证书流。 |
| [Comments](../../groupdocs.signature.options/digitalverifyoptions/comments) { get; set; } | 要验证的数字签名的注释。 |
| [Contact](../../groupdocs.signature.options/digitalverifyoptions/contact) { get; set; } | 要验证的签名联系人。 |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | 替代签名选项验证的附加扩展。 |
| [IssuerName](../../groupdocs.signature.options/digitalverifyoptions/issuername) { get; set; } | 要验证的证书的颁发者名称。值区分大小写。 如果设置此属性，验证将检查签名的颁发者名称是否包含或等于传递的值 |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | 有效的属性标志。 |
| [Location](../../groupdocs.signature.options/digitalverifyoptions/location) { get; set; } | 要验证的签名位置。 |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | 待验证的文档页码。如果未设置属性 - 文档的所有页面将在首次出现时进行验证。 最小值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | 指定要验证的页面的页面选项。 |
| [Password](../../groupdocs.signature.options/digitalverifyoptions/password) { get; set; } | 数字证书的密码（如果需要）。 |
| [Reason](../../groupdocs.signature.options/digitalverifyoptions/reason) { get; set; } | 验证数字签名的原因。 |
| [SignDateTimeFrom](../../groupdocs.signature.options/digitalverifyoptions/signdatetimefrom) { get; set; } | 要验证的数字签名的日期和时间范围。可空值将被忽略。 |
| [SignDateTimeTo](../../groupdocs.signature.options/digitalverifyoptions/signdatetimeto) { get; set; } | 要验证的数字签名的日期和时间范围。可空值将被忽略。 |
| [SubjectName](../../groupdocs.signature.options/digitalverifyoptions/subjectname) { get; set; } | 要验证的证书的主题专有名称。值区分大小写。 如果设置此属性，验证将检查签名主题名称是否包含或等于传递的值 |

### 评论

**学到更多**

* GroupDocs.Signature验证数字电子签名的基本用法： [如何电子验证文档中的数字签名](https://docs.groupdocs.com/display/signaturenet/Verify+Digital+signatures+in+the+document)
* GroupDocs.Signature 数字电子签名验证设置的高级用法： [文档中电子验证数字签名的高级使用和其他设置]()

### 也可以看看

* class [VerifyOptions](../verifyoptions)
* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->