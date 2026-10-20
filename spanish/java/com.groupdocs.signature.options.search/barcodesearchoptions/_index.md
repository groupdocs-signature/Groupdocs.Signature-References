---
title: "BarcodeSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda abstractas para firmas de código de barras."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Representa opciones de búsqueda abstractas para firmas de código de barras.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | Inicializa una nueva instancia de la clase SearchBarcodeOptions con valores predeterminados. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Inicializa una nueva instancia de la clase SearchBarcodeOptions con el valor del tipo de codificación. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | Inicializa una nueva instancia de la clase SearchBarcodeOptions con los valores de tipo de codificación y texto. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Especifica la propiedad Tipo de Codificación para buscar códigos de barras. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Especifica la propiedad Tipo de Codificación para buscar códigos de barras. |
|
|  | [getText()](#getText--) | Especifica el texto de la firma de código de barras si debe buscarse y coincidir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Especifica el texto de la firma de código de barras si debe buscarse y coincidir. |
|
|  | [getMatchType()](#getMatchType--) | Obtiene o establece la búsqueda del tipo de coincidencia de texto del código de barras. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtiene o establece la búsqueda del tipo de coincidencia de texto del código de barras. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtiene o establece la bandera para capturar el contenido de imagen del código de barras de la firma en la página del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtiene o establece la bandera para capturar el contenido de imagen del código de barras de la firma en la página del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


Inicializa una nueva instancia de la clase SearchBarcodeOptions con valores predeterminados.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


Inicializa una nueva instancia de la clase SearchBarcodeOptions con el valor del tipo de codificación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Especifica el tipo de codificación del código de barras. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


Inicializa una nueva instancia de la clase SearchBarcodeOptions con los valores de tipo de codificación y texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Especifica el tipo de codificación del código de barras. |
|
|  | texto | java.lang.String | Establece el texto de la firma del código de barras. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Especifica la propiedad Tipo de Codificación para buscar códigos de barras.
Si este valor no está establecido, la búsqueda se procesa para todos los tipos de código de barras compatibles


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Especifica la propiedad Tipo de Codificación para buscar códigos de barras.
Si este valor no está establecido, la búsqueda se procesa para todos los tipos de código de barras compatibles


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Especifica el texto de la firma de código de barras si debe buscarse y coincidir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Especifica el texto de la firma de código de barras si debe buscarse y coincidir.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtiene o establece la búsqueda del tipo de coincidencia de texto del código de barras. Se usa solo cuando la propiedad Text está establecida.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtiene o establece la búsqueda del tipo de coincidencia de texto del código de barras. Se usa solo cuando la propiedad Text está establecida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtiene o establece la bandera para capturar el contenido de imagen del código de barras de la firma en la página del documento.
Si esta bandera se establece en verdadero, el contenido de la imagen de la firma de código de barras mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtiene o establece la bandera para capturar el contenido de imagen del código de barras de la firma en la página del documento.
Si esta bandera se establece en verdadero, el contenido de la imagen de la firma de código de barras mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen de código de barras en el formato original.
Este formato de imagen se especifica en
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen de código de barras en formato .png.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma de código de barras cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa devolver el contenido de la imagen de código de barras en el formato original.
Este formato de imagen se especifica en
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de la imagen de código de barras en formato .png.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

