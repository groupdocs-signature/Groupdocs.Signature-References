---
title: "BarcodeSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de código de barras."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

Contiene propiedades de firma de código de barras.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | Inicializar el objeto BarcodeSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | Inicializar BarcodeSignature con parámetros predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Especifica el tipo de codificación del código de barras. |
|
|  | [getText()](#getText--) | Especifica el texto del código de barras. |
|
|  | [getFormat()](#getFormat--) | Especifica el formato de la imagen de firma de Barcode. |
|
|  | [getContent()](#getContent--) | Especifica el contenido de la imagen de datos binarios de Barcode del tipo |
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de Barcode Signature. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


Inicializar el objeto BarcodeSignature con el identificador de firma que se obtuvo después del proceso de búsqueda.
Este identificador único se utiliza para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identificador único de firma obtenido mediante el método Sign o Search de la clase Signature [Signature](../../com.groupdocs.signature/signature). |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


Inicializar BarcodeSignature con parámetros predeterminados.


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Especifica el tipo de codificación del código de barras.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


Especifica el texto del código de barras.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


Especifica el formato de la imagen de firma de Barcode.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


Especifica el contenido de la imagen de datos binarios de Barcode del tipo
Formato
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
Por defecto, esta propiedad no se establecerá.
Usar propiedad
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) para habilitar esta función.


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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| imagen | java.awt.image.BufferedImage |  |

