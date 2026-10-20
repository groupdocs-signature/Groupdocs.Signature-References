---
title: "QrCodeSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de código QR."
type: docs
weight: 16
url: /es/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

Contiene propiedades de firma de código QR.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | Inicializar el objeto QrCodeSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Especifica el tipo de codificación QR-code. |
|
|  | [getText()](#getText--) | Especifica el texto del código QR. |
|
|  | [getFormat()](#getFormat--) | Especifica el formato de la imagen de firma del código QR. |
|
|  | [getContent()](#getContent--) | Especifica el contenido de la imagen de datos binarios del código QR del tipo |
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | Obtener objeto del texto de firma QR-Code mediante deserialización. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | Obtener objeto del texto de firma QR-Code mediante deserialización. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de firma QR-Code. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


Inicializar el objeto QrCodeSignature con el identificador de firma que se obtuvo después del proceso de búsqueda.
Este identificador único se utiliza para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identificador único de la firma obtenido mediante el método de firma o búsqueda. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


Especifica el tipo de codificación QR-code.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


Especifica el texto del código QR.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Especifica el formato de la imagen de firma del código QR.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Especifica el contenido de la imagen de datos binarios del código QR del tipo
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Por defecto, esta propiedad no se establecerá.
Usar propiedad
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) para habilitar esta función.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


Obtener objeto del texto de firma QR-Code mediante deserialización.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | java.lang.Class<T> |  |

**Returns:**
T -
T
: Tipo de objeto a deserializar desde el texto QR-Code

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


Obtener objeto del texto de firma QR-Code mediante deserialización.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | Establecer implementación personalizada de cifrado de datos |


T
: Tipo de objeto a deserializar desde el texto QR-Code
|
| tipo | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Sobrescribe el método Equals para comparar propiedades de la firma


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | firma | java.lang.Object | Objeto de firma con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto de firma pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash de la firma

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clonar instancia de firma QR-Code.


**Returns:**
java.lang.Object - Devuelve la instancia de firma QR-code clonada.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| imagen | java.awt.image.BufferedImage |  |

