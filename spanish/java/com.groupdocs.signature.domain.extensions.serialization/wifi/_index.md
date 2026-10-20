---
title: "WiFi"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa los detalles de conexión de red WiFi."
type: docs
weight: 20
url: /es/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

Representa los detalles de conexión de red WiFi.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [WiFi()](#WiFi--) | Crea una instancia de VCard con valores predeterminados. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSSID()](#getSSID--) | Obtiene o establece el nombre del SSID de WiFi. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | Obtiene o establece el nombre del SSID de WiFi. |
|
|  | [getPassword()](#getPassword--) | Obtiene o establece la contraseña de WiFi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Obtiene o establece la contraseña de WiFi. |
|
|  | [getEncryption()](#getEncryption--) | Obtiene o establece el cifrado de WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | Obtiene o establece el cifrado de WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | Obtiene o establece si el SSID de WiFi está oculto. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | Obtiene o establece si el SSID de WiFi está oculto. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Sobrescribe el método Equals para comparar las propiedades de VCard |
|
|  | [hashCode()](#hashCode--) | Sobrescribe el método GetHashCode |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


Crea una instancia de VCard con valores predeterminados.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


Obtiene o establece el nombre del SSID de WiFi.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


Obtiene o establece el nombre del SSID de WiFi.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtiene o establece la contraseña de WiFi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtiene o establece la contraseña de WiFi.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


Obtiene o establece el cifrado de WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


Obtiene o establece el cifrado de WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Obtiene o establece si el SSID de WiFi está oculto.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Obtiene o establece si el SSID de WiFi está oculto.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sobrescribe el método Equals para comparar las propiedades de VCard


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
|  | obj | java.lang.Object | Objeto VCard con el que comparar. |
|

**Returns:**
boolean - Devuelve true si el objeto VCard pasado tiene el mismo tipo y todas sus propiedades son iguales a las propiedades de esta instancia.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sobrescribe el método GetHashCode


**Returns:**
int - Código hash de VCard

