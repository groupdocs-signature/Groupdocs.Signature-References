---
title: "TimeStamp"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa datos para obtener la marca de tiempo de un sitio externo."
type: docs
weight: 10
url: /es/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

Representa datos para obtener la marca de tiempo de un sitio externo.

## Constructores

| Constructor | Descripción |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | Instancia una nueva estructura de marca de tiempo. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getUrl()](#getUrl--) | URL del sitio de terceros. |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | URL del sitio de terceros. |
|
|  | [getUser()](#getUser--) | Usuario. |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | Usuario. |
|
|  | [getPassword()](#getPassword--) | Contraseña. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Contraseña. |
|
| [CloneTo(TimeStamp that)](#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(TimeStamp obj1, TimeStamp obj2)](#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
### TimeStamp() {#TimeStamp--}
```
public TimeStamp()
```


### TimeStamp(String url, String user, String password) {#TimeStamp-java.lang.String-java.lang.String-java.lang.String-}
```
public TimeStamp(String url, String user, String password)
```


Instancia una nueva estructura de marca de tiempo.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | url | java.lang.String | URL del sitio de terceros. |
|
|  | usuario | java.lang.String | Usuario. |
|
|  | contraseña | java.lang.String | Contraseña. |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


URL del sitio de terceros.


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


URL del sitio de terceros.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


Usuario.


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


Usuario.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Contraseña.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Contraseña.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| that | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### Clone() {#Clone--}
```
public TimeStamp Clone()
```




**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(TimeStamp obj1, TimeStamp obj2) {#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public static boolean equals(TimeStamp obj1, TimeStamp obj2)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
