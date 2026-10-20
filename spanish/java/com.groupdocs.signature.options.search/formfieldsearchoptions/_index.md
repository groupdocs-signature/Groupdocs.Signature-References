---
title: "FormFieldSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda abstractas para firmas de Form-field."
type: docs
weight: 13
url: /es/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

Representa opciones de búsqueda abstractas para firmas de Form-field.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | Inicializa una nueva instancia de la clase SearchFormFieldOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getType()](#getType--) | Especifica el tipo de firma de campo de formulario si debe buscarse. |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | Especifica el tipo de firma de campo de formulario si debe buscarse. |
|
|  | [getName()](#getName--) | Especifica el patrón de expresión regular del nombre de la firma de campo de formulario si debe buscarse. |
|
|  | [setName(String value)](#setName-java.lang.String-) | Especifica el patrón de expresión regular del nombre de la firma de campo de formulario si debe buscarse. |
|
|  | [getValue()](#getValue--) | Especifica el valor de la firma de campo de formulario si debe buscarse. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | Especifica el valor de la firma de campo de formulario si debe buscarse. |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


Inicializa una nueva instancia de la clase SearchFormFieldOptions con valores predeterminados.


### getType() {#getType--}
```
public final Integer getType()
```


Especifica el tipo de firma de campo de formulario si debe buscarse. El valor predeterminado es null.


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


Especifica el tipo de firma de campo de formulario si debe buscarse. El valor predeterminado es null.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


Especifica el patrón de expresión regular del nombre de la firma de campo de formulario si debe buscarse.
Puede usarlo simplemente como "text" o una expresión regular como "abc\\d+". El valor predeterminado es una cadena vacía.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Especifica el patrón de expresión regular del nombre de la firma de campo de formulario si debe buscarse.
Puede usarlo simplemente como "text" o una expresión regular como "abc\\d+". El valor predeterminado es una cadena vacía.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Especifica el valor de la firma de campo de formulario si debe buscarse. El valor predeterminado es null.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Especifica el valor de la firma de campo de formulario si debe buscarse. El valor predeterminado es null.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Object |  |

