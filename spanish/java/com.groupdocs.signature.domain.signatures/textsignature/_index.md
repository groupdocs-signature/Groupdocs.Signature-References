---
title: "TextSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de texto."
type: docs
weight: 18
url: /es/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Contiene propiedades de firma de texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | Inicializar el objeto TextSignature con el identificador de firma que se obtuvo después del proceso de búsqueda. |
|
| [TextSignature()](#TextSignature--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Especifica el texto en la firma. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Especifica el texto en la firma. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Especifica la implementación de la firma de texto. |
|
|  | [getNative()](#getNative--) | Especifica el atributo nativo. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | Especifica el atributo nativo. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clonar instancia de firma de texto. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


Inicializar el objeto TextSignature con el identificador de firma que se obtuvo después del proceso de búsqueda.
Este identificador único se utiliza para encontrar propiedades adicionales de esta firma en la capa de información de firmas del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | signatureId | java.lang.String | Identificador único de la firma obtenido mediante el método de firma o búsqueda. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


Especifica el texto en la firma.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Especifica el texto en la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Especifica la implementación de la firma de texto.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


Especifica el atributo nativo. Es verdadero si la firma es específica del documento.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


Especifica el atributo nativo. Es verdadero si la firma es específica del documento.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

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


Clonar instancia de firma de texto.


**Returns:**
java.lang.Object - Devuelve una instancia clonada de firma de texto.

