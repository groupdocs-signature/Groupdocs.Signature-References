---
title: "RadioButtonFormFieldSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de campo de formulario de entrada de botón de opción."
type: docs
weight: 14
url: /es/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

Contiene propiedades de firma de campo de formulario de entrada de botón de opción.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | Crea RadioButtonFieldSignature con un nombre predefinido. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crea RadioButtonFieldSignature con un nombre predefinido y una lista de elementos. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crea RadioButtonFieldSignature con un nombre predefinido, lista de elementos y valor seleccionado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSelected()](#getSelected--) | Contiene el valor seleccionado. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Contiene el valor seleccionado. |
|
|  | [getItems()](#getItems--) | Obtener o establecer la lista de opciones de los botones de radio. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Obtener o establecer la lista de opciones de los botones de radio. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de FormField Signature. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


Crea RadioButtonFieldSignature con un nombre predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


Crea RadioButtonFieldSignature con un nombre predefinido y una lista de elementos.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|
|  | items | java.util.List<java.lang.String> | Valores de la lista de botones de radio. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


Crea RadioButtonFieldSignature con un nombre predefinido, lista de elementos y valor seleccionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|
|  | items | java.util.List<java.lang.String> | Valores de la lista de botones de radio. |
|
|  | selected | java.lang.Object | Valor seleccionado. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Contiene el valor seleccionado.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Contiene el valor seleccionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Obtener o establecer la lista de opciones de los botones de radio.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Obtener o establecer la lista de opciones de los botones de radio.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.String> |  |

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

