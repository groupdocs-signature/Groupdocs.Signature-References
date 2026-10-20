---
title: "WiFi"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta i dettagli della connessione di rete WiFi."
type: docs
weight: 20
url: /it/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

Rappresenta i dettagli della connessione di rete WiFi.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [WiFi()](#WiFi--) | Crea un'istanza VCard con valori predefiniti. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSSID()](#getSSID--) | Ottiene o imposta il nome SSID del WiFi. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | Ottiene o imposta il nome SSID del WiFi. |
|
|  | [getPassword()](#getPassword--) | Ottiene o imposta la password del WiFi. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Ottiene o imposta la password del WiFi. |
|
|  | [getEncryption()](#getEncryption--) | Ottiene o imposta la crittografia WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | Ottiene o imposta la crittografia WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | Ottiene o imposta se il WiFi è SSID nascosto. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | Ottiene o imposta se il WiFi è SSID nascosto. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Sovrascrive il metodo Equals per confrontare le proprietà di VCard |
|
|  | [hashCode()](#hashCode--) | Sovrascrive il metodo GetHashCode |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


Crea un'istanza VCard con valori predefiniti.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


Ottiene o imposta il nome SSID del WiFi.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


Ottiene o imposta il nome SSID del WiFi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Ottiene o imposta la password del WiFi.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Ottiene o imposta la password del WiFi.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


Ottiene o imposta la crittografia WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


Ottiene o imposta la crittografia WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Ottiene o imposta se il WiFi è SSID nascosto.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Ottiene o imposta se il WiFi è SSID nascosto.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Sovrascrive il metodo Equals per confrontare le proprietà di VCard


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | obj | java.lang.Object | Oggetto VCard con cui confrontare. |
|

**Returns:**
boolean - Restituisce true se l'oggetto VCard passato ha lo stesso tipo e tutte le sue proprietà sono uguali a quelle di questa istanza.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Sovrascrive il metodo GetHashCode


**Returns:**
int - codice hash VCard

