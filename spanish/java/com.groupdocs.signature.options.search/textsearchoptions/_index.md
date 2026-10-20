---
title: "TextSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones de búsqueda para firmas de Texto."
type: docs
weight: 18
url: /es/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

Representa opciones de búsqueda para firmas de Texto.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getText()](#getText--) | Especifica el texto de la firma para coincidir en la búsqueda. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Especifica el texto de la firma para coincidir en la búsqueda. |
|
|  | [getMatchType()](#getMatchType--) | Obtiene o establece el tipo de coincidencia de texto en la búsqueda. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Obtiene o establece el tipo de coincidencia de texto en la búsqueda. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | Especifica la implementación de la firma de texto para buscar. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | Especifica la implementación de la firma de texto para buscar. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


Inicializa una nueva instancia de la clase TextSearchOptions con valores predeterminados.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
```


Inicializa una nueva instancia de la clase TextSearchOptions con un valor de texto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | texto | java.lang.String | Establece el texto de la firma de texto. |
|

### getText() {#getText--}
```
public final String getText()
```


Especifica el texto de la firma para coincidir en la búsqueda.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Especifica el texto de la firma para coincidir en la búsqueda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Obtiene o establece el tipo de coincidencia de texto en la búsqueda.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Obtiene o establece el tipo de coincidencia de texto en la búsqueda.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


Especifica la implementación de la firma de texto para buscar.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


Especifica la implementación de la firma de texto para buscar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

