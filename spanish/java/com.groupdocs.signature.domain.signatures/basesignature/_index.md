---
title: "BaseSignature"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Describe la clase base para firmas."
type: docs
weight: 11
url: /es/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

Describe la clase base para firmas.

## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | Especifica el tipo de firma. |
|
|  | [getPageNumber()](#getPageNumber--) | Especifica la página en la que se encontró la firma. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | Especifica la página en la que se encontró la firma. |
|
|  | [getSignatureId()](#getSignatureId--) | Identificador único de la firma para modificarla en el documento mediante los métodos Actualizar o Eliminar. |
|
|  | [isSignature()](#isSignature--) | Obtener o establecer la bandera que indica si este componente es una firma o contenido del documento. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | Obtener o establecer la bandera que indica si este componente es una firma o contenido del documento. |
|
|  | [getDeleted()](#getDeleted--) | Obtener o establecer la bandera que indica si esta firma fue eliminada del documento. |
|
|  | [getCreatedOn()](#getCreatedOn--) | Obtener o establecer la fecha de creación de la firma. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | Obtener o establecer la fecha de creación de la firma. |
|
|  | [getModifiedOn()](#getModifiedOn--) | Obtener o establecer la fecha de modificación de la firma. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | Obtener o establecer la fecha de modificación de la firma. |
|
|  | [getTop()](#getTop--) | Especifica la posición superior de la firma. |
|
|  | [setTop(int value)](#setTop-int-) | Especifica la posición superior de la firma. |
|
|  | [getLeft()](#getLeft--) | Especifica la posición izquierda de la firma. |
|
|  | [setLeft(int value)](#setLeft-int-) | Especifica la posición izquierda de la firma. |
|
|  | [getWidth()](#getWidth--) | Especifica el ancho de la firma. |
|
|  | [setWidth(int value)](#setWidth-int-) | Especifica el ancho de la firma. |
|
|  | [getHeight()](#getHeight--) | Especifica la altura de la firma. |
|
|  | [setHeight(int value)](#setHeight-int-) | Especifica la altura de la firma. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar propiedades de la firma |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


Especifica el tipo de firma. La firma digital tendrá esta propiedad.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


Especifica la página en la que se encontró la firma.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


Especifica la página en la que se encontró la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Identificador único de la firma para modificarla en el documento mediante los métodos Actualizar o Eliminar.
Esta propiedad se establecerá automáticamente después de que se llame al método Sign o Search.
Si esta propiedad se guardó antes, puede establecerse manualmente para manipular la firma.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


Obtener o establecer la bandera que indica si este componente es una firma o contenido del documento.
Esta propiedad se utiliza con el método Update para establecer el elemento como firma (true) o como elemento del documento (false).


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


Obtener o establecer la bandera que indica si este componente es una firma o contenido del documento.
Esta propiedad se utiliza con el método Update para establecer el elemento como firma (true) o como elemento del documento (false).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


Obtener o establecer la bandera que indica si esta firma fue eliminada del documento.
Esta propiedad se usa solo para los registros del historial del documento para mantener la lista de firmas eliminadas.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


Obtener o establecer la fecha de creación de la firma.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


Obtener o establecer la fecha de creación de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


Obtener o establecer la fecha de modificación de la firma.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


Obtener o establecer la fecha de modificación de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


Especifica la posición superior de la firma.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


Especifica la posición superior de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


Especifica la posición izquierda de la firma.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


Especifica la posición izquierda de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


Especifica el ancho de la firma.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


Especifica el ancho de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Especifica la altura de la firma.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Especifica la altura de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

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
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String - 
