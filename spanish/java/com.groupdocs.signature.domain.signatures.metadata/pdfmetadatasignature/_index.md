---
title: "PdfMetadataSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de metadatos PDF."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

Contiene propiedades de firma de metadatos PDF.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | Crea una firma de metadatos PDF con nombre predefinido y valor vacío |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | Crea una firma de metadatos PDF con valores predefinidos |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | Crea una firma de metadatos PDF con valores predefinidos |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | La etiqueta de prefijo del nombre de la firma de metadatos PDF. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | La etiqueta de prefijo del nombre de la firma de metadatos PDF. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de Metadata Signature. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | Clona la instancia de Pdf Metadata Signature con el valor dado. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


Crea una firma de metadatos PDF con nombre predefinido y valor vacío


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre de Pdf Metadata Signature |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


Crea una firma de metadatos PDF con valores predefinidos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de firma de Metadatos |
|
|  | valor | java.lang.Object | Valor de la firma de Metadatos |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


Crea una firma de metadatos PDF con valores predefinidos


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de firma de Metadatos |
|
|  | valor | java.lang.Object | Valor de la firma de Metadatos |
|
|  | tag | java.lang.String | Etiqueta de prefijo de la firma de Metadatos |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


La etiqueta de prefijo del nombre de la firma de metadatos PDF. Por defecto, esta propiedad está establecida en "xmp".
Los valores posibles son


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


La etiqueta de prefijo del nombre de la firma de metadatos PDF. Por defecto, esta propiedad está establecida en "xmp".
Los valores posibles son


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

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


Clona la instancia de Metadata Signature.


**Returns:**
java.lang.Object - Devuelve la instancia clonada de Metadata Signature

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


Clona la instancia de Pdf Metadata Signature con el valor dado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | valor | java.lang.Object | Valor para el nuevo objeto clonado. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

