---
title: IDocumentInfo
second_title: GroupDocs.Editor for Java API Reference
description: Defines document description properties.
type: docs
weight: 12
url: /java/com.groupdocs.signature.domain.documentpreview/idocumentinfo/
---```
public interface IDocumentInfo
```

Defines document description properties.
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
| [getFileType()](#getFileType--) | File format type |
| [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | File format type |
| [getSize()](#getSize--) | Document size in bytes. |
| [setSize(long value)](#setSize-long-) | Document size in bytes. |
| [getTextSignatures()](#getTextSignatures--) | Collection of document text signatures added or updated by [TextSignature](../../com.groupdocs.signature.domain.signatures/textsignature) methods. |
| [getImageSignatures()](#getImageSignatures--) | Collection of document image signatures added or updated by [ImageSignature](../../com.groupdocs.signature.domain.signatures/imagesignature) methods. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Collection of document digital signatures added or updated by [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) methods. |
| [getBarcodeSignatures()](#getBarcodeSignatures--) | Collection of document barcode signatures added or updated by [BarcodeSignature](../../com.groupdocs.signature.domain.signatures/barcodesignature) methods. |
| [getQrCodeSignatures()](#getQrCodeSignatures--) | Collection of document QR-code signatures added or updated by [QrCodeSignature](../../com.groupdocs.signature.domain.signatures/qrcodesignature) methods. |
| [getFormFieldSignatures()](#getFormFieldSignatures--) | Collection of document Form Field signatures added or updated by [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) methods. |
| [getFormFields()](#getFormFields--) | Collection of all existing supported Form Fields in the document. |
| [getProcessLogs()](#getProcessLogs--) | Collection of document history process logs. |
| [getSignatures()](#getSignatures--) | Collection of document all types signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
### getPageCount() {#getPageCount--}
```
public abstract int getPageCount()
```


Document pages count.

**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public abstract void setPageCount(int value)
```


Document pages count.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPages() {#getPages--}
```
public abstract List<PageInfo> getPages()
```


Collection of document pages descriptions.

**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public abstract void setPages(List<PageInfo> value)
```


Collection of document pages descriptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public abstract int getWidthForMaxHeight()
```


Specifies width for max page height.

**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public abstract void setWidthForMaxHeight(int value)
```


Specifies width for max page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public abstract int getMaxPageHeight()
```


Specifies max page height.

**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public abstract void setMaxPageHeight(int value)
```


Specifies max page height.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFileType() {#getFileType--}
```
public abstract FileType getFileType()
```


File format type

**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public abstract void setFileType(FileType value)
```


File format type

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public abstract long getSize()
```


Document size in bytes.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public abstract void setSize(long value)
```


Document size in bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getTextSignatures() {#getTextSignatures--}
```
public abstract List<TextSignature> getTextSignatures()
```


Collection of document text signatures added or updated by [TextSignature](../../com.groupdocs.signature.domain.signatures/textsignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public abstract List<ImageSignature> getImageSignatures()
```


Collection of document image signatures added or updated by [ImageSignature](../../com.groupdocs.signature.domain.signatures/imagesignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract List<DigitalSignature> getDigitalSignatures()
```


Collection of document digital signatures added or updated by [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public abstract List<BarcodeSignature> getBarcodeSignatures()
```


Collection of document barcode signatures added or updated by [BarcodeSignature](../../com.groupdocs.signature.domain.signatures/barcodesignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public abstract List<QrCodeSignature> getQrCodeSignatures()
```


Collection of document QR-code signatures added or updated by [QrCodeSignature](../../com.groupdocs.signature.domain.signatures/qrcodesignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public abstract List<FormFieldSignature> getFormFieldSignatures()
```


Collection of document Form Field signatures added or updated by [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) methods.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public abstract List<FormFieldSignature> getFormFields()
```


Collection of all existing supported Form Fields in the document. This property is supported only for Pdf and Word Processing document types.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getProcessLogs() {#getProcessLogs--}
```
public abstract List<ProcessLog> getProcessLogs()
```


Collection of document history process logs.

**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public abstract List<BaseSignature> getSignatures()
```


Collection of document all types signatures [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
