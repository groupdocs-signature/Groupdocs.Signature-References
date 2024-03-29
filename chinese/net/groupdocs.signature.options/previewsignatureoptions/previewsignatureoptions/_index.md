---
title: PreviewSignatureOptions
second_title: GroupDocs.Signature for .NET API 参考
description: 初始化 PreviewSignatureOptions 对象
type: docs
weight: 10
url: /zh/net/groupdocs.signature.options/previewsignatureoptions/previewsignatureoptions/
---
## PreviewSignatureOptions(SignOptions, CreateSignatureStream) {#constructor}

初始化 PreviewSignatureOptions 对象。

```csharp
public PreviewSignatureOptions(SignOptions signOptions, CreateSignatureStream createSignatureStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signOptions | SignOptions | 为其生成预览的签名选项。 |
| createSignatureStream | CreateSignatureStream | 定义创建输出签名预览流的方法的委托。 |

### 也可以看看

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* 命名空间 [GroupDocs.Signature.Options](../../previewsignatureoptions)
* 部件 [GroupDocs.Signature](../../../)

---

## PreviewSignatureOptions(SignOptions, CreateSignatureStream, ReleaseSignatureStream) {#constructor_1}

初始化 PreviewSignatureOptions 对象。

```csharp
public PreviewSignatureOptions(SignOptions signOptions, 
    CreateSignatureStream createSignatureStream, ReleaseSignatureStream releaseSignatureStream)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| signOptions | SignOptions | 为其生成预览的签名选项。 |
| createSignatureStream | CreateSignatureStream | 定义创建输出签名预览流的方法的委托。 |
| releaseSignatureStream | ReleaseSignatureStream | 定义释放输出签名预览流方法的委托。 |

### 也可以看看

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* delegate [ReleaseSignatureStream](../../releasesignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* 命名空间 [GroupDocs.Signature.Options](../../previewsignatureoptions)
* 部件 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
