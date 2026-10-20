---
title: "FormFieldSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de campo de formulario."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

Contiene propiedades de firma de campo de formulario.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getName()](#getName--) | Especifica un nombre único para el campo de formulario. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Especifica un nombre único para el campo de formulario. |
|
|  | [getType()](#getType--) | Especifica el tipo de campo de formulario. |
|
|  | [getValue()](#getValue--) | Especifica el objeto de datos del campo de formulario. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Especifica el objeto de datos del campo de formulario. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de FormField Signature. |
|
### getName() {#getName--}
```
public final String getName()
```


Especifica un nombre único para el campo de formulario.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Especifica un nombre único para el campo de formulario.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Especifica el tipo de campo de formulario.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Especifica el objeto de datos del campo de formulario.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Especifica el objeto de datos del campo de formulario.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

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


Clona la instancia de FormField Signature.


**Returns:**
java.lang.Object - Devuelve una instancia clonada de FormField Signature.

