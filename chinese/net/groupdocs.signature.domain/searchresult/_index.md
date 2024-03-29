---
title: SearchResult
second_title: GroupDocs.Signature for .NET API 参考
description: 在指定文档中搜索签名的结果
type: docs
weight: 830
url: /zh/net/groupdocs.signature.domain/searchresult/
---
## SearchResult class

在指定文档中搜索签名的结果。

```csharp
public class SearchResult : IEnumerable<BaseSignature>, IResult
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [DestinDocumentSize](../../groupdocs.signature.domain/searchresult/destindocumentsize) { get; } | 返回目标文档大小。对于 Search 方法，它总是返回 0. |
| [ProcessingTime](../../groupdocs.signature.domain/searchresult/processingtime) { get; } | 以毫秒为单位返回搜索过程的执行时间。 |
| [Signatures](../../groupdocs.signature.domain/searchresult/signatures) { get; } | 找到的签名列表[`BaseSignature`](../basesignature). |
| [SourceDocumentSize](../../groupdocs.signature.domain/searchresult/sourcedocumentsize) { get; } | 返回源文件大小 |
| [Succeeded](../../groupdocs.signature.domain/searchresult/succeeded) { get; } | 找到的签名列表[`BaseSignature`](../basesignature).此列表将始终等于[`Signatures`](./signatures)财产. |
| [TotalSignatures](../../groupdocs.signature.domain/searchresult/totalsignatures) { get; } | 返回搜索进程处理过的签名总数 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [GetEnumerator](../../groupdocs.signature.domain/searchresult/getenumerator)() | 返回枚举器。 |
| [ToList&lt;T&gt;](../../groupdocs.signature.domain/searchresult/tolist)() | 提供到强类型签名列表的转换。 |

### 也可以看看

* class [BaseSignature](../basesignature)
* interface [IResult](../iresult)
* 命名空间 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
