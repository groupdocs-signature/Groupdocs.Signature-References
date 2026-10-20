---
title: "DocumentInfo"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Definierar dokumentbeskrivningsegenskaper."
type: docs
weight: 10
url: /sv/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definierar dokumentbeskrivningsegenskaper.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Initierar en ny instans av [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)-klassen. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Antal dokumentsidor. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Antal dokumentsidor. |
|
|  | [getPages()](#getPages--) | Samling av beskrivningar av dokumentsidor. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Samling av beskrivningar av dokumentsidor. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Anger bredd för maximal sidhöjd. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Anger bredd för maximal sidhöjd. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Anger maximal sidhöjd. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Anger maximal sidhöjd. |
|
|  | [getFileType()](#getFileType--) | Filformatstyp. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Filformatstyp. |
|
|  | [getSize()](#getSize--) | Dokumentstorlek i byte. |
|
|  | [setSize(long value)](#setSize-long-) | Dokumentstorlek i byte. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Samling av dokumentets textsignaturer. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Samling av dokumentets bildsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder. |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Samling av dokumentets digitala signaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder. |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Samling av dokumentets streckkodssignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder. |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Samling av dokumentets QR-kodsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder. |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Samling av dokumentets formulärfältsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder. |
|
|  | [getFormFields()](#getFormFields--) | Samling av alla befintliga stödda formulärfält i dokumentet. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Samling av dokumentets metadata-signaturer. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Samling av dokumentets historikprocesser som Sign, Update, Delete. |
|
|  | [getSignatures()](#getSignatures--) | Samling av dokumentets alla typer av signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Initierar en ny instans av [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)-klassen.


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Antal dokumentsidor.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Antal dokumentsidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Samling av beskrivningar av dokumentsidor.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Samling av beskrivningar av dokumentsidor.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Anger bredd för maximal sidhöjd.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Anger bredd för maximal sidhöjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Anger maximal sidhöjd.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Anger maximal sidhöjd.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Filformatstyp.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Filformatstyp.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Dokumentstorlek i byte.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Dokumentstorlek i byte.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Samling av dokumentets textsignaturer.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Samling av dokumentets bildsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Samling av dokumentets digitala signaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Samling av dokumentets streckkodssignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Samling av dokumentets QR-kodsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Samling av dokumentets formulärfältsignaturer som lagts till eller uppdaterats av [Signature](../../com.groupdocs.signature/signature) metoder.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Samling av alla befintliga stödda formulärfält i dokumentet. Denna egenskap stöds endast för Pdf- och Word Processing-dokumenttyper.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Samling av dokumentets metadata-signaturer.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Samling av dokumentets historikprocesser som Sign, Update, Delete.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Samling av dokumentets alla typer av signaturer [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
