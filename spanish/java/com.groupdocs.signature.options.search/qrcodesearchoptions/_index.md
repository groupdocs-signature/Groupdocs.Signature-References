---
title: "QrCodeSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda abstractas para firmas de QR-Code."
type: docs
weight: 16
url: /es/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

Representa opciones de búsqueda abstractas para firmas de QR-Code.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con un valor de tipo de codificación. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores de tipo de codificación y texto. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Especifica la propiedad Tipo de codificación para buscar códigos QR. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | Especifica la propiedad Tipo de codificación para buscar códigos QR. |
|
|  | [getText()](#getText--) | Especifica el texto de la firma QR-Code si debe buscarse y coincidir. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Especifica el texto de la firma QR-Code si debe buscarse y coincidir. |
|
|  | [getMatchType()](#getMatchType--) | Obtiene o establece la búsqueda del tipo de coincidencia de texto QR-Code. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtiene o establece la búsqueda del tipo de coincidencia de texto QR-Code. |
|
|  | [getDataEncryption()](#getDataEncryption--) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code. |
|
|  | [getReturnContent()](#getReturnContent--) | Obtiene o establece la bandera para capturar el contenido de imagen QR-Code de la firma en la página del documento. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | Obtiene o establece la bandera para capturar el contenido de imagen QR-Code de la firma en la página del documento. |
|
|  | [getReturnContentType()](#getReturnContentType--) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores predeterminados.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


Inicializa una nueva instancia de la clase QRCodeSearchOptions con un valor de tipo de codificación.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Especifica el tipo de codificación QR-Code. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


Inicializa una nueva instancia de la clase QRCodeSearchOptions con valores de tipo de codificación y texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | Especifica el tipo de codificación QR-Code. |
|
|  | texto | java.lang.String | Establece el texto de la firma QR-Code. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Especifica la propiedad Tipo de codificación para buscar códigos QR.
Si este valor no está establecido, la búsqueda se procesa para todos los tipos de QR-Code compatibles.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


Especifica la propiedad Tipo de codificación para buscar códigos QR.
Si este valor no está establecido, la búsqueda se procesa para todos los tipos de QR-Code compatibles.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Especifica el texto de la firma QR-Code si debe buscarse y coincidir.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Especifica el texto de la firma QR-Code si debe buscarse y coincidir.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtiene o establece la búsqueda del tipo de coincidencia de texto QR-Code. Se usa solo cuando la propiedad Text está establecida.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtiene o establece la búsqueda del tipo de coincidencia de texto QR-Code. Se usa solo cuando la propiedad Text está establecida.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


Obtiene o establece la implementación de la interfaz [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) para codificar y decodificar el texto o las propiedades de datos de la firma QR-Code.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


Obtiene o establece la bandera para capturar el contenido de imagen QR-Code de la firma en la página del documento.
Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar en el formato requerido.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
Por defecto, esta opción está deshabilitada.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


Obtiene o establece la bandera para capturar el contenido de imagen QR-Code de la firma en la página del documento.
Si esta bandera se establece en true, el contenido de imagen de la firma QR-Code mantendrá los datos de imagen sin procesar en el formato requerido.
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


Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen QR-Code en el formato original.
Este formato de imagen se especifica en
QrCodeSignature.Format
()
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QR-Code en el .png original.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


Especifica el tipo de archivo del contenido de imagen devuelto de la firma QR-Code cuando la propiedad ReturnContent está habilitada.
Por defecto se establece en Null. Eso significa que se devolverá el contenido de imagen QR-Code en el formato original.
Este formato de imagen se especifica en
QrCodeSignature.Format
()
Los valores compatibles posibles son: FileType.JPEG, FileType.PNG, FileType.BMP.
Si el formato proporcionado no es compatible, se devolverá el contenido de imagen QR-Code en el .png original.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

