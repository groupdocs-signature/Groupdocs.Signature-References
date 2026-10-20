---
title: "DocumentInfo"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Define propiedades de descripción del documento."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.documentpreview/documentinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.documentpreview.IDocumentInfo](../../com.groupdocs.signature.domain.documentpreview/idocumentinfo)
```
public class DocumentInfo implements IDocumentInfo
```

Define propiedades de descripción del documento.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DocumentInfo()](#DocumentInfo--) | Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo). |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getPageCount()](#getPageCount--) | Recuento de páginas del documento. |
|
|  | [setPageCount(int value)](#setPageCount-int-) | Recuento de páginas del documento. |
|
|  | [getPages()](#getPages--) | Colección de descripciones de páginas del documento. |
|
|  | [setPages(List<PageInfo> value)](#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--) | Colección de descripciones de páginas del documento. |
|
|  | [getWidthForMaxHeight()](#getWidthForMaxHeight--) | Especifica el ancho para la altura máxima de página. |
|
|  | [setWidthForMaxHeight(int value)](#setWidthForMaxHeight-int-) | Especifica el ancho para la altura máxima de página. |
|
|  | [getMaxPageHeight()](#getMaxPageHeight--) | Especifica la altura máxima de página. |
|
|  | [setMaxPageHeight(int value)](#setMaxPageHeight-int-) | Especifica la altura máxima de página. |
|
|  | [getFileType()](#getFileType--) | Tipo de formato de archivo. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | Tipo de formato de archivo. |
|
|  | [getSize()](#getSize--) | Tamaño del documento en bytes. |
|
|  | [setSize(long value)](#setSize-long-) | Tamaño del documento en bytes. |
|
| [addPage(int pageWidth, int pageHeight, int pageIndex)](#addPage-int-int-int-) |  |
|  | [getTextSignatures()](#getTextSignatures--) | Colección de firmas de texto del documento. |
|
|  | [getImageSignatures()](#getImageSignatures--) | Colección de firmas de imagen del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getDigitalSignatures()](#getDigitalSignatures--) | Colección de firmas digitales del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getBarcodeSignatures()](#getBarcodeSignatures--) | Colección de firmas de código de barras del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getQrCodeSignatures()](#getQrCodeSignatures--) | Colección de firmas de código QR del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFieldSignatures()](#getFormFieldSignatures--) | Colección de firmas de campo de formulario del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature). |
|
|  | [getFormFields()](#getFormFields--) | Colección de todos los campos de formulario compatibles existentes en el documento. |
|
|  | [getMetadataSignatures()](#getMetadataSignatures--) | Colección de firmas de metadatos del documento. |
|
|  | [getProcessLogs()](#getProcessLogs--) | Colección de procesos de historial del documento como Firmar, Actualizar, Eliminar. |
|
|  | [getSignatures()](#getSignatures--) | Colección de todas las firmas de tipos del documento [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
### DocumentInfo() {#DocumentInfo--}
```
public DocumentInfo()
```


Inicializa una nueva instancia de la clase [DocumentInfo](../../com.groupdocs.signature.domain.documentpreview/documentinfo).


### getPageCount() {#getPageCount--}
```
public final int getPageCount()
```


Recuento de páginas del documento.


**Returns:**
int
### setPageCount(int value) {#setPageCount-int-}
```
public final void setPageCount(int value)
```


Recuento de páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getPages() {#getPages--}
```
public final List<PageInfo> getPages()
```


Colección de descripciones de páginas del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.PageInfo>
### setPages(List<PageInfo> value) {#setPages-java.util.List-com.groupdocs.signature.domain.PageInfo--}
```
public final void setPages(List<PageInfo> value)
```


Colección de descripciones de páginas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<com.groupdocs.signature.domain.PageInfo> |  |

### getWidthForMaxHeight() {#getWidthForMaxHeight--}
```
public final int getWidthForMaxHeight()
```


Especifica el ancho para la altura máxima de página.


**Returns:**
int
### setWidthForMaxHeight(int value) {#setWidthForMaxHeight-int-}
```
public final void setWidthForMaxHeight(int value)
```


Especifica el ancho para la altura máxima de página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getMaxPageHeight() {#getMaxPageHeight--}
```
public final int getMaxPageHeight()
```


Especifica la altura máxima de página.


**Returns:**
int
### setMaxPageHeight(int value) {#setMaxPageHeight-int-}
```
public final void setMaxPageHeight(int value)
```


Especifica la altura máxima de página.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


Tipo de formato de archivo.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


Tipo de formato de archivo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Tamaño del documento en bytes.


**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Tamaño del documento en bytes.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | long |  |

### addPage(int pageWidth, int pageHeight, int pageIndex) {#addPage-int-int-int-}
```
public final PageInfo addPage(int pageWidth, int pageHeight, int pageIndex)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Colección de firmas de texto del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.TextSignature>
### getImageSignatures() {#getImageSignatures--}
```
public final List<ImageSignature> getImageSignatures()
```


Colección de firmas de imagen del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.ImageSignature>
### getDigitalSignatures() {#getDigitalSignatures--}
```
public final List<DigitalSignature> getDigitalSignatures()
```


Colección de firmas digitales del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature>
### getBarcodeSignatures() {#getBarcodeSignatures--}
```
public final List<BarcodeSignature> getBarcodeSignatures()
```


Colección de firmas de código de barras del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BarcodeSignature>
### getQrCodeSignatures() {#getQrCodeSignatures--}
```
public final List<QrCodeSignature> getQrCodeSignatures()
```


Colección de firmas de código QR del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.QrCodeSignature>
### getFormFieldSignatures() {#getFormFieldSignatures--}
```
public final List<FormFieldSignature> getFormFieldSignatures()
```


Colección de firmas de campo de formulario del documento añadidas o actualizadas mediante los métodos [Signature](../../com.groupdocs.signature/signature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getFormFields() {#getFormFields--}
```
public final List<FormFieldSignature> getFormFields()
```


Colección de todos los campos de formulario compatibles existentes en el documento. Esta propiedad solo es compatible con los tipos de documento Pdf y Word Processing.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature>
### getMetadataSignatures() {#getMetadataSignatures--}
```
public final List<MetadataSignature> getMetadataSignatures()
```


Colección de firmas de metadatos del documento.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature>
### getProcessLogs() {#getProcessLogs--}
```
public final List<ProcessLog> getProcessLogs()
```


Colección de procesos de historial del documento como Firmar, Actualizar, Eliminar.


**Returns:**
java.util.List<com.groupdocs.signature.domain.ProcessLog>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


Colección de todas las firmas de tipos del documento [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
