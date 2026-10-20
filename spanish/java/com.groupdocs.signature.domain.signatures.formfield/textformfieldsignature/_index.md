---
title: "TextFormFieldSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de campo de formulario de entrada de texto para documento PDF"
type: docs
weight: 15
url: /es/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Contiene propiedades de firma de campo de formulario de entrada de texto para documento PDF

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | Crea PdfTextFormFieldSignature con un nombre predefinido. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | Crea PdfTextFormFieldSignature con un nombre predefinido. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Obtiene o establece el texto de la entrada de texto del campo de formulario. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Obtiene o establece el texto de la entrada de texto del campo de formulario. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de FormField Signature. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


Crea PdfTextFormFieldSignature con un nombre predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


Crea PdfTextFormFieldSignature con un nombre predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|
|  | texto | java.lang.String | Texto del objeto de campo de formulario. |
|

### getText() {#getText--}
```
public final String getText()
```


Obtiene o establece el texto de la entrada de texto del campo de formulario.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Obtiene o establece el texto de la entrada de texto del campo de formulario.


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


Clona la instancia de FormField Signature.


**Returns:**
java.lang.Object - Devuelve una instancia clonada de FormField Signature.

