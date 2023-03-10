---
title: Signature
second_title: GroupDocs.Signature for .NET API 参考
description: 表示控制文档签名过程的主类
type: docs
weight: 1880
url: /zh/net/groupdocs.signature/signature/
---
## Signature class

表示控制文档签名过程的主类。

```csharp
public class Signature : IDisposable
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | 初始化新实例[`Signature`](../signature)类与 stream. 提供的文档 |
| [Signature](signature#constructor_4)(string) | 初始化新实例[`Signature`](../signature)文件路径提供文档的类实例. |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | 初始化新实例[`Signature`](../signature)带有流和加载选项提供的文档的类LoadOptions. |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | 初始化新实例[`Signature`](../signature)具有流提供的文档的类实例和[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_5)(string, LoadOptions) | 初始化新实例[`Signature`](../signature)具有文件路径提供的文档的类实例和LoadOptions. |
| [Signature](signature#constructor_7)(string, SignatureSettings) | 初始化新实例[`Signature`](../signature)具有文件路径提供的文档的类实例和[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | 初始化新实例[`Signature`](../signature)带有流提供的文档的类实例，加载选项LoadOptions和设置[`SignatureSettings`](../signaturesettings). |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | 初始化新实例[`Signature`](../signature)具有文件路径提供的文档的类实例，LoadOptions和[`SignatureSettings`](../signaturesettings). |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 删除通过的签名[`BaseSignature`](../../groupdocs.signature.domain/basesignature)来自文档. |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 删除传递的签名列表[`BaseSignature`](../../groupdocs.signature.domain/basesignature)来自文档. |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | 删除特定类型列表的签名[`SignatureType`](../../groupdocs.signature.domain/signaturetype)来自文档. 只有通过 Sign 方法添加并标记为 Signatures 的签名[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature)将被删除。 支持以下签名类型：文本、图像、数字、条形码、二维码 |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 删除传递的签名列表[`BaseSignature`](../../groupdocs.signature.domain/basesignature)来自文档. |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | 删除特定类型的签名[`SignatureType`](../../groupdocs.signature.domain/signaturetype)来自文档. 只有通过 Sign 方法添加并标记为 Signatures 的签名[`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature)将被删除。 支持以下签名类型：文本、图像、数字、条形码、二维码 |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | 从文档中删除其特定签名 ID 的签名。 |
| [Dispose](../../groupdocs.signature/signature/dispose)() | 实现IDisposable接口清理内部资源 |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | 生成文档页面预览。 |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | 获取有关文档页面的信息：它们的大小、 最大页面高度、具有最大高度的页面的宽度。 |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | 在文档中搜索签名[`SearchOptions`](../../groupdocs.signature.options/searchoptions)列表. |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | 在文档中搜索指定的签名类型[`SignatureType`](../../groupdocs.signature.domain/signaturetype)值. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_3)(SearchOptions) | 在文档中搜索签名[`SearchOptions`](../../groupdocs.signature.options/searchoptions)选项. |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_2)(SignatureType) | 在文档中搜索确切类型的签名[`SignatureType`](../../groupdocs.signature.domain/signaturetype)值. |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | 签署文件集合[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | 签署文件[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | 签署文件集合[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到指定的文件路径. |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | 签署文件[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到指定的文件路径. |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | 签署文件集合[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到具有预定义的流[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | 签署文件[`SignOptions`](../../groupdocs.signature.options/signoptions)并将结果保存到具有预定义的流[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | 签署文件集合[`SignOptions`](../../groupdocs.signature.options/signoptions)并使用预定义将结果保存到指定的文件路径[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | 签署文件[`SignOptions`](../../groupdocs.signature.options/signoptions)并使用预定义将结果保存到指定的文件路径[`SaveOptions`](../../groupdocs.signature.options/saveoptions). |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | 更新通过签名[`BaseSignature`](../../groupdocs.signature.domain/basesignature)在文档中. |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | 更新通过的签名[`BaseSignature`](../../groupdocs.signature.domain/basesignature)在文档中. |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | 使用 VerifyOptions 数据列表验证文档签名。 |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 使用给定的 VerifyOptions 数据验证文档签名。 |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 根据给定的 SignOptions 生成签名预览。[`SignOptions`](../../groupdocs.signature.options/signoptions) |

## 活动

| 姓名 | 描述 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 签名搜索过程完成时发生。 |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 签名搜索进程更改时发生。 |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 签名搜索过程开始时发生。 |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | 文档签名过程完成时发生。 |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | 文档签名进程更改时发生。 |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | 文档签名过程开始时发生。 |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 签名验证过程完成时发生。 |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 签名验证过程进度更改时发生。 |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 签名验证过程开始时发生。 |

### 评论

**了解更多**

* 有关 GroupDocs 的更多信息。签名功能： [GroupDocs.Signature 开发者指南](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 也可以看看

* 命名空间 [GroupDocs.Signature](../../groupdocs.signature)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
