---
title: "DigitalSearchOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa opciones base para la búsqueda de firmas Digitales"
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

Representa opciones base para la búsqueda de firmas Digitales

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | Inicializa una nueva instancia de la clase DigitalSearchOptions con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getComments()](#getComments--) | Comentarios de la firma Digital a buscar. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | Comentarios de la firma Digital a buscar. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Rango de fecha y hora de la firma Digital a buscar. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Rango de fecha y hora de la firma Digital a buscar. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | Rango de fecha y hora de la firma Digital a buscar. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Rango de fecha y hora de la firma Digital a buscar. |
|
|  | [getSubjectName()](#getSubjectName--) | Para valores no vacíos especifica el nombre distinguido del sujeto del certificado a buscar. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Para valores no vacíos especifica el nombre distinguido del sujeto del certificado a buscar. |
|
|  | [getIssuerName()](#getIssuerName--) | Para valores no vacíos especifica el nombre distinguido del emisor del certificado a buscar. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Para valores no vacíos especifica el nombre distinguido del emisor del certificado a buscar. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


Inicializa una nueva instancia de la clase DigitalSearchOptions con valores predeterminados.


### getComments() {#getComments--}
```
public final String getComments()
```


Comentarios de la firma Digital a buscar.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Comentarios de la firma Digital a buscar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


Rango de fecha y hora de la firma Digital a buscar. Los valores nulos se ignorarán.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


Rango de fecha y hora de la firma Digital a buscar. Los valores nulos se ignorarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


Rango de fecha y hora de la firma Digital a buscar. Los valores nulos se ignorarán.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


Rango de fecha y hora de la firma Digital a buscar. Los valores nulos se ignorarán.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Para valores no vacíos especifica el nombre distinguido del sujeto del certificado a buscar.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Para valores no vacíos especifica el nombre distinguido del sujeto del certificado a buscar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Para valores no vacíos especifica el nombre distinguido del emisor del certificado a buscar.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Para valores no vacíos especifica el nombre distinguido del emisor del certificado a buscar.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

