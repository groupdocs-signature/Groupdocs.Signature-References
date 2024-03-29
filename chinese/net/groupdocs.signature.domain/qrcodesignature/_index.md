---
title: QrCodeSignature
second_title: GroupDocs.Signature for .NET API 参考
description: 包含二维码签名属性
type: docs
weight: 790
url: /zh/net/groupdocs.signature.domain/qrcodesignature/
---
## QrCodeSignature class

包含二维码签名属性。

```csharp
public class QrCodeSignature : BaseSignature
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [QrCodeSignature](qrcodesignature)(string) | 使用搜索过程后获得的签名标识符初始化 QrCodeSignature 对象。 此唯一标识符用于从文档签名信息层中查找此签名的其他属性。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [Content](../../groupdocs.signature.domain/qrcodesignature/content) { get; } | 指定类型的二维码二进制数据图像内容[`Format`](./format). 默认情况下不会设置此属性。 使用属性[`ReturnContent`](../../groupdocs.signature.options/qrcodesearchoptions/returncontent)启用此功能。 |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 获取或设置签名创建日期。 |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 获取指示此签名是否已从文档中删除的标志。 此属性仅用于文档历史日志记录以保留已删除签名的列表。 |
| [EncodeType](../../groupdocs.signature.domain/qrcodesignature/encodetype) { get; } | 指定二维码编码类型。 |
| [Format](../../groupdocs.signature.domain/qrcodesignature/format) { get; } | 指定二维码签名图片格式。 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 指定签名高度。 |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 获取或设置标志以指示此组件是签名还是文档内容。 此属性与 Update 方法一起使用以将元素设置为签名 (true) 或文档元素 (false)。 |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 指定签名的左侧位置。 |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 获取或设置签名修改日期。 |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 指定找到的页面签名。 |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | 用于通过 Update 或 Delete 方法修改文档中签名的唯一签名标识符。 此属性将在调用 Sign 或 Search 方法后自动设置。 如果此属性在可以手动设置之前保存以操作签名。 |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 指定签名类型。 |
| [Text](../../groupdocs.signature.domain/qrcodesignature/text) { get; } | 指定二维码的文本。 |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 指定签名的顶部位置。 |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 指定签名宽度。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/qrcodesignature/clone)() | 克隆二维码签名实例. |
| override [Equals](../../groupdocs.signature.domain/qrcodesignature/equals)(object) | 覆盖 Equals 方法以比较签名属性 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata)() | 通过反序列化从二维码签名文本中获取对象。 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/qrcodesignature/getdata#getdata_1)(IDataEncryption) | 通过反序列化从二维码签名文本中获取对象。 |
| override [GetHashCode](../../groupdocs.signature.domain/qrcodesignature/gethashcode)() | 覆盖 GetHashCode 方法 |

### 也可以看看

* class [BaseSignature](../basesignature)
* 命名空间 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 部件 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
