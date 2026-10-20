---
title: "ComboboxFormFieldSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Contiene propiedades de firma de campo de formulario de entrada de lista desplegable."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

Contiene propiedades de firma de campo de formulario de entrada de lista desplegable.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | Crea ComboboxFormFieldSignature con un nombre predefinido. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | Crea ComboboxFormFieldSignature con un nombre predefinido y una lista de opciones. |
|
|  | [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | Crea ComboboxFormFieldSignature con un nombre predefinido, lista de opciones y valor seleccionado. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSelected()](#getSelected--) | Obtener o establecer el valor seleccionado. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | Obtener o establecer el valor seleccionado. |
|
|  | [getItems()](#getItems--) | Obtener o establecer la lista de opciones del combo-box. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Obtener o establecer la lista de opciones del combo-box. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
|  | [deepClone()](#deepClone--) | Clona la instancia de FormField Signature. |
|
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


Crea ComboboxFormFieldSignature con un nombre predefinido.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


Crea ComboboxFormFieldSignature con un nombre predefinido y una lista de opciones.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|
|  | items | java.util.List<java.lang.String> | Valores de la lista del combo-box. |
|

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


Crea ComboboxFormFieldSignature con un nombre predefinido, lista de opciones y valor seleccionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | name | java.lang.String | Nombre del objeto de campo de formulario. |
|
|  | items | java.util.List<java.lang.String> | Valores de la lista del combo-box. |
|
|  | selected | java.lang.Object | Valor seleccionado. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


Obtener o establecer el valor seleccionado.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


Obtener o establecer el valor seleccionado.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Obtener o establecer la lista de opciones del combo-box.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Obtener o establecer la lista de opciones del combo-box.


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

