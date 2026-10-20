---
title: "ImageSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de imagen."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

Contiene propiedades de firma de imagen.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | Inicializa el objeto ImageSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. |
|
|  | [ImageSignature()](#ImageSignature--) | Inicializa ImageSignature con parámetros predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSize()](#getSize--) | Especifica el tamaño en bytes de la imagen de la firma. |
|
|  | [setSize(int value)](#setSize-int-) | Especifica el tamaño en bytes de la imagen de la firma. |
|
|  | [getFormat()](#getFormat--) | Especifica el formato de la imagen de la firma. |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | Especifica el formato de la imagen de la firma. |
|
|  | [getContent()](#getContent--) | Especifica el contenido de datos binarios de la imagen de tipo |
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de Barcode Signature. |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


Inicializa el objeto ImageSignature con el identificador de firma que se obtuvo después del proceso de búsqueda.
Este identificador único se utiliza para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identificador único de firma obtenido mediante el método Sign o Search de la clase Signature [Signature](../../com.groupdocs.signature/signature). |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


Inicializa ImageSignature con parámetros predeterminados.


### getSize() {#getSize--}
```
public final int getSize()
```


Especifica el tamaño en bytes de la imagen de la firma.


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Especifica el tamaño en bytes de la imagen de la firma.



**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Especifica el formato de la imagen de la firma.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


Especifica el formato de la imagen de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


Especifica el contenido de datos binarios de la imagen de tipo
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Por defecto, esta propiedad no se establecerá.
Usar propiedad
ImageSearchOptions.ReturnContent
({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) para habilitar esta función.


**Returns:**
byte[]
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


Clonar instancia de Barcode Signature.


**Returns:**
java.lang.Object - Devuelve una instancia clonada de Barcode Signature.

