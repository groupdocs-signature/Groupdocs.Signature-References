---
title: "PreviewSignatureOptions"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示签名预览选项。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.options/previewsignatureoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewSignatureOptions
```

表示签名预览选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)](#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-) | 初始化 PreviewSignatureOptions 对象。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getSignatureId()](#getSignatureId--) | 用于区分签名的唯一值。 |
|
|  | [setSignatureId(String value)](#setSignatureId-java.lang.String-) | 用于区分签名的唯一值。 |
|
|  | [getSignOptions()](#getSignOptions--) | 用于生成预览的签名选项。 |
|
|  | [setSignOptions(SignOptions value)](#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-) | 用于生成预览的签名选项。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 获取或设置预览图像的格式。 |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | 获取或设置预览图像的格式。 |
|
### PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory) {#PreviewSignatureOptions-com.groupdocs.signature.options.sign.SignOptions-com.groupdocs.signature.options.PageSignatureStreamFactory-}
```
public PreviewSignatureOptions(SignOptions signOptions, PageSignatureStreamFactory pageStreamFactory)
```


初始化 PreviewSignatureOptions 对象。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) | 用于生成预览的签名选项。 |
|
|  | pageStreamFactory | [PageSignatureStreamFactory](../../com.groupdocs.signature.options/pagesignaturestreamfactory) | 定义创建输出页面预览流方法的接口。 |
|

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


用于区分签名的唯一值。
使用 SignatureId 来标识预览选项。


**Returns:**
java.lang.String
### setSignatureId(String value) {#setSignatureId-java.lang.String-}
```
public final void setSignatureId(String value)
```


用于区分签名的唯一值。
使用 SignatureId 来标识预览选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getSignOptions() {#getSignOptions--}
```
public final SignOptions getSignOptions()
```


用于生成预览的签名选项。


**Returns:**
[SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
### setSignOptions(SignOptions value) {#setSignOptions-com.groupdocs.signature.options.sign.SignOptions-}
```
public final void setSignOptions(SignOptions value)
```


用于生成预览的签名选项。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


获取或设置预览图像的格式。
默认值为 PNG


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


获取或设置预览图像的格式。
默认值为 PNG


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

