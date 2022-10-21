---
title: PreviewOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 初始化 PreviewOptions 对象
type: docs
weight: 10
url: /zh/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, params int[]) {#constructor_1}

初始化 PreviewOptions 对象。

```csharp
public PreviewOptions(CreatePageStream createPageStream, params int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 定义创建输出页面预览流的方法的委托。 |
| pageNumbers | Int32[] | 所需的页码 |

### 也可以看看

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* 命名空间 [GroupDocs.Signature.Options](../../previewoptions)
* 部件 [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, params int[]) {#constructor}

初始化 PreviewOptions 对象。

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    params int[] pageNumbers)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 定义创建输出页面预览流的方法的委托。 |
| releasePageStream | ReleasePageStream | 定义释放输出页面预览流的方法的委托。 |
| pageNumbers | Int32[] | 所需的页码 |

### 也可以看看

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* 命名空间 [GroupDocs.Signature.Options](../../previewoptions)
* 部件 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->