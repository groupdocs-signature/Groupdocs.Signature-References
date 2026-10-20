---
title: "DocumentInfo"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Definisce le proprietà di descrizione del documento."
type: docs
weight: 10
url: /it/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Definisce le proprietà di descrizione del documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Conteggio delle pagine del documento. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Conteggio delle pagine del documento. |
|
|  | [getPages()](#getPages--) | Raccolta di descrizioni delle pagine del documento. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Raccolta di descrizioni delle pagine del documento. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Specifica la larghezza per l'altezza massima della pagina. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Specifica la larghezza per l'altezza massima della pagina. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Specifica l'altezza massima della pagina. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Specifica l'altezza massima della pagina. |
|
|  | [getFileType()](#getFileType--) | Tipo di formato file. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Tipo di formato file. |
|
|  | [getSize()](#getSize--) | Dimensione del documento in byte. |
|
|  | [setSize(long value)](#setSize-long-) | Dimensione del documento in byte. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Raccolta di firme di testo del documento. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Raccolta di firme immagine del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Raccolta di firme digitali del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Raccolta di firme barcode del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Raccolta di firme QR-code del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Raccolta di firme di campi modulo del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFields()](#getFormFields--) | Raccolta di tutti i campi modulo supportati esistenti nel documento. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Raccolta di firme di metadati del documento. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Raccolta dei processi della cronologia del documento come Firma, Aggiorna, Elimina. |
|
|  | [getSignatures()](#getSignatures--) | Raccolta di firme di tutti i tipi di documento [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Inizializza una nuova istanza della classe [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Conteggio delle pagine del documento.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Conteggio delle pagine del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Raccolta di descrizioni delle pagine del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Raccolta di descrizioni delle pagine del documento.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Specifica la larghezza per l'altezza massima della pagina.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Specifica la larghezza per l'altezza massima della pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Specifica l'altezza massima della pagina.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Specifica l'altezza massima della pagina.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Tipo di formato file.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Tipo di formato file.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Dimensione del documento in byte.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Dimensione del documento in byte.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Raccolta di firme di testo del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Raccolta di firme immagine del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Raccolta di firme digitali del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Raccolta di firme barcode del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Raccolta di firme QR-code del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Raccolta di firme di campi modulo del documento aggiunte o aggiornate dai metodi [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Raccolta di tutti i campi modulo supportati esistenti nel documento. Questa proprietà è supportata solo per i tipi di documento Pdf e Word Processing.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Raccolta di firme di metadati del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Raccolta dei processi della cronologia del documento come Firma, Aggiorna, Elimina.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Raccolta di firme di tutti i tipi di documento [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
