---
title: DocumentInfo
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Defines document description properties.
type: docs
weight: 10
url: /nodejs-java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Defines document description properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [DocumentInfo()](#DocumentInfo--) | Initializes a new instance of the [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPageCount()](#getPageCount--) | Document pages count. |
| [setPageCount(int value)](#setPageCount-int-) | Document pages count. |
| [getPages()](#getPages--) | Collection of document pages descriptions. |
| [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Collection of document pages descriptions. |
| [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Specifies width for max page height. |
| [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Specifies width for max page height. |
| [getMaxPageHeight()](#getMaxPageHeight--) | Specifies max page height. |
| [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Specifies max page height. |
| [getFileType()](#getFileType--) | File format type. |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | File format type. |
| [getSize()](#getSize--) | Document size in bytes. |
| [setSize(long value)](#setSize-long-) | Document size in bytes. |
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
| [getTextSignatures()](#getTextSignatures--) | Collection of document text signatures. |
| [getImageSignatures()](#getImageSignatures--) | Collection of document image signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Collection of document digital signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods. |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | Collection of document barcode signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods. |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | Collection of document QR-code signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods. |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | Collection of document Form Field signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods. |
| [getFormFields()](#getFormFields--) | Collection of all existing supported Form Fields in the document. |
| [getMetadataSignatures()](#getMetadataSignatures--) | Collection of document Metadata signatures. |
| [getProcessLogs()](#getProcessLogs--) | Collection of document history processes like Sign, Update, Delete. |
| [getSignatures()](#getSignatures--) | Collection of document all types signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Initializes a new instance of the [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo) class.

### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Document pages count.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Document pages count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Collection of document pages descriptions.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Collection of document pages descriptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Specifies width for max page height.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Specifies width for max page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Specifies max page height.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Specifies max page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


File format type.

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


File format type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Document size in bytes.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Document size in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parameter | Type | Description |
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


Collection of document text signatures.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Collection of document image signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Collection of document digital signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Collection of document barcode signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Collection of document QR-code signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Collection of document Form Field signatures added or updated by [Signature](../../com.groupdocs.signature/signature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Collection of all existing supported Form Fields in the document. This property is supported only for Pdf and Word Processing document types.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Collection of document Metadata signatures.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Collection of document history processes like Sign, Update, Delete.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Collection of document all types signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
