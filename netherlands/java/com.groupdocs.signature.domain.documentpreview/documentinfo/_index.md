---
title: "DocumentInfo"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Definieert eigenschappen voor de documentbeschrijving."
type: docs
weight: 10
url: /nl/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definieert eigenschappen voor de documentbeschrijving.

## Constructors

| Constructor | Beschrijving |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)‑klasse. |
|
## Methoden

| Methode | Beschrijving |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Aantal documentpagina's. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Aantal documentpagina's. |
|
|  | [getPages()](#getPages--) | Collectie van beschrijvingen van documentpagina's. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Collectie van beschrijvingen van documentpagina's. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Specificeert de breedte voor de maximale paginahoogte. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Specificeert de breedte voor de maximale paginahoogte. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Specificeert de maximale paginahoogte. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Specificeert de maximale paginahoogte. |
|
|  | [getFileType()](#getFileType--) | Bestandsformaat type. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Bestandsformaat type. |
|
|  | [getSize()](#getSize--) | Documentgrootte in bytes. |
|
|  | [setSize(long value)](#setSize-long-) | Documentgrootte in bytes. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Collectie van documentteksthandtekeningen. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Collectie van documentafbeeldinghandtekeningen toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden. |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Collectie van digitale documenthandtekeningen toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden. |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Collectie van barcodehandtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden. |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Collectie van QR-codehandtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden. |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Collectie van Form Field-handtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden. |
|
|  | [getFormFields()](#getFormFields--) | Collectie van alle bestaande ondersteunde Form Fields in het document. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Collectie van metadatahandtekeningen van het document. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Collectie van documentgeschiedenisprocessen zoals Sign, Update, Delete. |
|
|  | [getSignatures()](#getSignatures--) | Collectie van alle typen handtekeningen van het document [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Initialiseert een nieuw exemplaar van de [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo)‑klasse.


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Aantal documentpagina's.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Aantal documentpagina's.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Collectie van beschrijvingen van documentpagina's.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Collectie van beschrijvingen van documentpagina's.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Specificeert de breedte voor de maximale paginahoogte.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Specificeert de breedte voor de maximale paginahoogte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Specificeert de maximale paginahoogte.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Specificeert de maximale paginahoogte.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Bestandsformaat type.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Bestandsformaat type.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Documentgrootte in bytes.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Documentgrootte in bytes.


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Collectie van documentteksthandtekeningen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Collectie van documentafbeeldinghandtekeningen toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Collectie van digitale documenthandtekeningen toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Collectie van barcodehandtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Collectie van QR-codehandtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Collectie van Form Field-handtekeningen van het document toegevoegd of bijgewerkt door [Signature](../../com.groupdocs.signature/signature) methoden.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Collectie van alle bestaande ondersteunde formuliervelden in het document. Deze eigenschap wordt alleen ondersteund voor Pdf- en Word-verwerkingsdocumenttypen.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Collectie van metadatahandtekeningen van het document.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Collectie van documentgeschiedenisprocessen zoals Sign, Update, Delete.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Collectie van alle typen handtekeningen van het document [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
