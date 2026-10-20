---
title: "WiFi"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Representerar detaljer för WiFi-nätverksanslutning."
type: docs
weight: 20
url: /sv/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

Representerar detaljer för WiFi-nätverksanslutning.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
|  | [WiFi()](#WiFi--) | Skapar VCard-instans med standardvärden. |
|
## Metoder

| Metod | Beskrivning |
| --- | --- |
|  | [getSSID()](#getSSID--) | Hämtar eller anger WiFi SSID-namn. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | Hämtar eller anger WiFi SSID-namn. |
|
|  | [getPassword()](#getPassword--) | Hämtar eller anger WiFi-lösenord. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Hämtar eller anger WiFi-lösenord. |
|
|  | [getEncryption()](#getEncryption--) | Hämtar eller anger WiFi-kryptering [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | Hämtar eller anger WiFi-kryptering [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | Hämtar eller anger om WiFi är ett dolt SSID. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | Hämtar eller anger om WiFi är ett dolt SSID. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Skriver över Equals‑metoden för att jämföra VCard‑egenskaper. |
|
|  | [hashCode()](#hashCode--) | Åsidosätter GetHashCode‑metoden. |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


Skapar VCard-instans med standardvärden.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


Hämtar eller anger WiFi SSID-namn.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


Hämtar eller anger WiFi SSID-namn.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Hämtar eller anger WiFi-lösenord.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Hämtar eller anger WiFi-lösenord.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


Hämtar eller anger WiFi-kryptering [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


Hämtar eller anger WiFi-kryptering [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Hämtar eller anger om WiFi är ett dolt SSID.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Hämtar eller anger om WiFi är ett dolt SSID.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Skriver över Equals‑metoden för att jämföra VCard‑egenskaper.


**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | obj | java.lang.Object | VCard-objekt att jämföra med. |
|

**Returns:**
boolean - Returnerar true om det överförda VCard-objektet har samma typ och alla dess egenskaper är lika med den här instansens egenskaper.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Åsidosätter GetHashCode‑metoden.


**Returns:**
int - VCard hashkod

