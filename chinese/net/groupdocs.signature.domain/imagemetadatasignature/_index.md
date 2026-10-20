---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API 参考"
description: "包含图像元数据签名属性。"
type: docs
weight: 740
url: /zh/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

包含图像元数据签名属性。

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | 创建具有 Id 和值的 Image Metadata Signature |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 获取或设置签名创建日期。 |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | 获取或设置 [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) 接口的实现，以编码和解码签名 Value 属性。 |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 获取指示此签名是否已从文档中删除的标志。此属性仅用于文档历史日志记录，以保留已删除签名的列表。 |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | 只读值，用于获取标准 Image Metadata signature 的描述 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 指定签名的高度。 |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Image Metadata 签名的标识符。请参阅包含具有预定义 Id 值的标准 Signature 的 ImageMetadataSignatures 类。 |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 获取或设置标志，以指示此组件是签名还是文档内容。此属性与 Update 方法一起使用，以将元素设置为签名（true）或文档元素（false）。 |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 指定签名的左侧位置。 |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 获取或设置签名修改日期。 |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 指定唯一的元数据名称。 |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 指定发现签名的页面。 |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | 唯一的签名标识符，用于通过 Update 或 Delete 方法修改文档中的签名。调用 Sign 或 Search 方法后，此属性会自动设置。如果此属性之前已保存，则可以手动设置以操作签名。 |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 指定签名的类型。 |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | 只读值，用于获取 Metadata 值的大小 |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 指定签名的顶部位置。 |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | 指定元数据值类型。 |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | 指定元数据对象。 |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 指定签名的宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | 克隆 Metadata Signature 实例。 |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | 使用给定值克隆 Image Metadata Signature 实例。 |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | 覆盖 Equals 方法以比较签名属性 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | 在反序列化后从 Metadata Signature Value 获取对象。 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | 在反序列化后从 Metadata Signature Text 获取对象。 |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | 覆盖 GetHashCode 方法 |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | 转换为布尔值。 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | 转换为 DateTime。 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | 转换为 DateTime。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | 转换为 Decimal。 |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | 转换为 Decimal。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | 转换为 Double。 |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | 转换为 Double。 |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | 转换为 integer。 |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | 转换为 long。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | 转换为 float。 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | 转换为 float。 |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | 使用覆盖的 ToString() 方法转换为 String |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | 使用指定格式转换为 String |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 使用指定格式转换为 String |

### 另请参见

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
