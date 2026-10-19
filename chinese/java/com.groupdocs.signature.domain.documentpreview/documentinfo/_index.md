---
title: "DocumentInfo"
second_title: "GroupDocs.Signature for Java API 参考"
description: "定义文档描述属性。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

定义文档描述属性。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | 初始化 [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) 类的新实例。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | 文档页数。 |
|
|  | [setPageCount(int value)](#setPageCount-int-) | 文档页数。 |
|
|  | [getPages()](#getPages--) | 文档页面描述的集合。 |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | 文档页面描述的集合。 |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | 指定最大页面高度的宽度。 |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | 指定最大页面高度的宽度。 |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | 指定最大页面高度。 |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | 指定最大页面高度。 |
|
|  | [getFileType()](#getFileType--) | 文件格式类型。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | 文件格式类型。 |
|
|  | [getSize()](#getSize--) | 文档大小（字节）。 |
|
|  | [setSize(long value)](#setSize-long-) | 文档大小（字节）。 |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | 文档文本签名的集合。 |
|
|  | [getImageSignatures()](#getImageSignatures--) | 通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档图像签名的集合。 |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | 通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档数字签名的集合。 |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | 通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档条形码签名集合。 |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | 通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档二维码签名集合。 |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | 通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档表单字段签名集合。 |
|
|  | [getFormFields()](#getFormFields--) | 文档中所有现有受支持的表单字段集合。 |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | 文档元数据签名集合。 |
|
|  | [getProcessLogs()](#getProcessLogs--) | 文档历史过程集合，例如签名、更新、删除。 |
|
|  | [getSignatures()](#getSignatures--) | 文档所有类型签名的集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。 |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


初始化 [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) 类的新实例。


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


文档页数。


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


文档页数。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


文档页面描述的集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


文档页面描述的集合。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


指定最大页面高度的宽度。


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


指定最大页面高度的宽度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


指定最大页面高度。


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


指定最大页面高度。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


文件格式类型。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


文件格式类型。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


文档大小（字节）。


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


文档大小（字节）。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| pageWidth | int |  |
| pageHeight | int |  |
| pageIndex | int |  |

**Returns:**
[PageInfo](../../com.groupdocs.signature.domain/pageinfo)
### getTextSignatures() {#getTextSignatures--}
```
public final List<TextSignature> getTextSignatures()
```


文档文本签名的集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档图像签名的集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档数字签名的集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档条形码签名集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档二维码签名集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


通过 [Signature](../../com.groupdocs.signature/signature) 方法添加或更新的文档表单字段签名集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


文档中所有现有受支持的表单字段集合。此属性仅在 PDF 和 Word 处理文档类型中受支持。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


文档元数据签名集合。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


文档历史过程集合，例如签名、更新、删除。


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


文档所有类型签名的集合 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
