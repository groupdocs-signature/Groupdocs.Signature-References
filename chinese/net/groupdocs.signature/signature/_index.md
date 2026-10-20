---
title: "签名"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "表示控制文档签名过程的主类。"
type: docs
weight: 2170
url: /zh/net/groupdocs.signature/signature/
---
## Signature class

表示控制文档签名过程的主类。

```csharp
public class Signature : IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Signature](signature#constructor)(Stream) | 使用流提供的文档初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_4)(string) | 使用文件路径提供的文档初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_1)(Stream, LoadOptions) | 使用流提供的文档和加载选项 LoadOptions 初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_3)(Stream, SignatureSettings) | 使用流提供的文档和 [`SignatureSettings`](../signaturesettings) 初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_5)(string, LoadOptions) | 使用文件路径提供的文档和 LoadOptions 初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_7)(string, SignatureSettings) | 使用文件路径提供的文档和 [`SignatureSettings`](../signaturesettings) 初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_2)(Stream, LoadOptions, SignatureSettings) | 使用流提供的文档、加载选项 LoadOptions 和设置 [`SignatureSettings`](../signaturesettings) 初始化 [`Signature`](../signature) 类的新实例。 |
| [Signature](signature#constructor_6)(string, LoadOptions, SignatureSettings) | 使用文件路径提供的文档、LoadOptions 和 [`SignatureSettings`](../signaturesettings) 初始化 [`Signature`](../signature) 类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Delete](../../groupdocs.signature/signature/delete#delete)(BaseSignature) | 从文档中删除传入的签名 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_3)(List&lt;BaseSignature&gt;) | 从文档中删除传入的签名列表 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_4)(List&lt;SignatureType&gt;) | 从文档中删除特定类型列表的签名 [`SignatureType`](../../groupdocs.signature.domain/signaturetype)。仅删除通过 Sign 方法添加并标记为签名 [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 的签名。支持以下签名类型：文本、图像、数字、条形码、二维码。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_5)(List&lt;string&gt;) | 从文档中删除传入的签名列表 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_2)(SignatureType) | 从文档中删除特定类型的签名 [`SignatureType`](../../groupdocs.signature.domain/signaturetype)。仅删除通过 Sign 方法添加并标记为签名 [`IsSignature`](../../groupdocs.signature.domain/basesignature/issignature) 的签名。支持以下签名类型：文本、图像、数字、条形码、二维码。 |
| [Delete](../../groupdocs.signature/signature/delete#delete_1)(string) | 从文档中删除具有特定签名 Id 的签名。 |
| [Dispose](../../groupdocs.signature/signature/dispose)() | 实现 IDisposable 接口以清理内部资源。 |
| [GeneratePreview](../../groupdocs.signature/signature/generatepreview)(PreviewOptions) | 生成文档页面预览。 |
| [GetDocumentInfo](../../groupdocs.signature/signature/getdocumentinfo)() | 获取有关文档页面的信息：它们的尺寸、最大页面高度以及具有最大高度的页面的宽度。 |
| [Search](../../groupdocs.signature/signature/search#search_3)(Func&lt;BaseSignature, bool&gt;) | 使用所有可用的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。 |
| [Search](../../groupdocs.signature/signature/search#search_1)(List&lt;SearchOptions&gt;) | 通过 [`SearchOptions`](../../groupdocs.signature.options/searchoptions) 列表在文档中搜索签名。 |
| [Search](../../groupdocs.signature/signature/search#search)(params SignatureType[]) | 通过 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) 值在文档中搜索指定的签名类型。 |
| [Search](../../groupdocs.signature/signature/search#search_2)(List&lt;SearchOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 使用提供的搜索选项在文档中搜索签名，并根据指定的谓词过滤结果。 |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_5)(SearchOptions) | 通过 [`SearchOptions`](../../groupdocs.signature.options/searchoptions) 选项在文档中搜索签名。 |
| [Search&lt;T&gt;](../../groupdocs.signature/signature/search#search_4)(SignatureType) | 通过 [`SignatureType`](../../groupdocs.signature.domain/signaturetype) 值在文档中搜索精确类型的签名。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_2)(Stream, List&lt;SignOptions&gt;) | 使用一组 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign)(Stream, SignOptions) | 使用 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_6)(string, List&lt;SignOptions&gt;) | 使用一组 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_4)(string, SignOptions) | 使用 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并将结果保存到指定的文件路径。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_3)(Stream, List&lt;SignOptions&gt;, SaveOptions) | 使用一组 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../groupdocs.signature.options/saveoptions) 将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_1)(Stream, SignOptions, SaveOptions) | 使用 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../groupdocs.signature.options/saveoptions) 将结果保存到流中。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_7)(string, List&lt;SignOptions&gt;, SaveOptions) | 使用一组 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../groupdocs.signature.options/saveoptions) 将结果保存到指定的文件路径。 |
| [Sign](../../groupdocs.signature/signature/sign#sign_5)(string, SignOptions, SaveOptions) | 使用 [`SignOptions`](../../groupdocs.signature.options/signoptions) 对文档进行签名，并使用预定义的 [`SaveOptions`](../../groupdocs.signature.options/saveoptions) 将结果保存到指定的文件路径。 |
| [Update](../../groupdocs.signature/signature/update#update)(BaseSignature) | 在文档中更新传入的签名 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)。 |
| [Update](../../groupdocs.signature/signature/update#update_1)(List&lt;BaseSignature&gt;) | 在文档中更新传入的签名集合 [`BaseSignature`](../../groupdocs.signature.domain/basesignature)。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_1)(List&lt;VerifyOptions&gt;) | 使用 VerifyOptions 数据列表验证文档签名。 |
| [Verify](../../groupdocs.signature/signature/verify#verify)(VerifyOptions) | 使用给定的 VerifyOptions 数据验证文档签名。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_3)(List&lt;VerifyOptions&gt;, Func&lt;BaseSignature, bool&gt;) | 使用所有可用的验证选项验证文档签名，并根据指定的谓词过滤结果。此方法首先搜索匹配验证选项的签名，使用谓词进行过滤，然后仅验证这些过滤后的签名。 |
| [Verify](../../groupdocs.signature/signature/verify#verify_2)(VerifyOptions, Func&lt;BaseSignature, bool&gt;) | 使用提供的验证选项验证文档签名，并根据指定的谓词过滤结果。此方法首先搜索匹配验证选项的签名，使用谓词进行过滤，然后仅验证这些过滤后的签名。 |
| static [GenerateSignaturePreview](../../groupdocs.signature/signature/generatesignaturepreview)(PreviewSignatureOptions) | 根据给定的 SignOptions 生成签名预览。 [`SignOptions`](../../groupdocs.signature.options/signoptions) |

## 事件

| 名称 | 描述 |
| --- | --- |
| event [SearchCompleted](../../groupdocs.signature/signature/searchcompleted) | 当签名搜索过程完成时触发。 |
| event [SearchProgress](../../groupdocs.signature/signature/searchprogress) | 当签名搜索过程进度更改时触发。 |
| event [SearchStarted](../../groupdocs.signature/signature/searchstarted) | 当签名搜索过程启动时触发。 |
| event [SignCompleted](../../groupdocs.signature/signature/signcompleted) | 当文档签名过程完成时触发。 |
| event [SignProgress](../../groupdocs.signature/signature/signprogress) | 当文档签署过程进度更改时发生。 |
| event [SignStarted](../../groupdocs.signature/signature/signstarted) | 当文档签署过程开始时发生。 |
| event [VerifyCompleted](../../groupdocs.signature/signature/verifycompleted) | 当签名验证过程完成时发生。 |
| event [VerifyProgress](../../groupdocs.signature/signature/verifyprogress) | 当签名验证过程进度更改时发生。 |
| event [VerifyStarted](../../groupdocs.signature/signature/verifystarted) | 当签名验证过程开始时发生。 |

### 备注

**Learn more**

了解更多 GroupDocs.Signature 功能： [GroupDocs.Signature Developer Guide](https://docs.groupdocs.com/display/signaturenet/Developer+Guide)

### 另请参见

* namespace [GroupDocs.Signature](../../groupdocs.signature)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
