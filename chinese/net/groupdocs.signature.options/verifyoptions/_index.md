---
title: VerifyOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 保留验证文档的选项
type: docs
weight: 1700
url: /zh/net/groupdocs.signature.options/verifyoptions/
---
## VerifyOptions class

保留验证文档的选项。

```csharp
public abstract class VerifyOptions
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/verifyoptions/allpages) { get; set; } | 标志以验证每个文档页面。默认值为真。 |
| [Extensions](../../groupdocs.signature.options/verifyoptions/extensions) { get; set; } | 替代签名选项验证的附加扩展。 |
| [IsValid](../../groupdocs.signature.options/verifyoptions/isvalid) { get; } | 有效的属性标志。 |
| virtual [PageNumber](../../groupdocs.signature.options/verifyoptions/pagenumber) { get; set; } | 待验证的文档页码。如果未设置属性 - 文档的所有页面将在首次出现时进行验证。 最小值为 1. |
| virtual [PagesSetup](../../groupdocs.signature.options/verifyoptions/pagessetup) { get; set; } | 指定要验证的页面的页面选项。 |

### 也可以看看

* 命名空间 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
