---
title: "WiFi"
second_title: "GroupDocs.Signature für Java API-Referenz"
description: "Stellt Details zur WiFi-Netzwerkverbindung dar."
type: docs
weight: 20
url: /de/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

Stellt Details zur WiFi-Netzwerkverbindung dar.

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
|  | [WiFi()](#WiFi--) | Erstellt eine VCard-Instanz mit Standardwerten. |
|
## Methoden

| Methode | Beschreibung |
| --- | --- |
|  | [getSSID()](#getSSID--) | Liest oder setzt den WiFi‑SSID‑Namen. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | Liest oder setzt den WiFi‑SSID‑Namen. |
|
|  | [getPassword()](#getPassword--) | Liest oder setzt das WiFi‑Passwort. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | Liest oder setzt das WiFi‑Passwort. |
|
|  | [getEncryption()](#getEncryption--) | Liest oder setzt die WiFi‑Verschlüsselung [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | Liest oder setzt die WiFi‑Verschlüsselung [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | Liest oder setzt, ob das WiFi eine versteckte SSID ist. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | Liest oder setzt, ob das WiFi eine versteckte SSID ist. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Überschreibt die Equals‑Methode, um VCard‑Eigenschaften zu vergleichen |
|
|  | [hashCode()](#hashCode--) | Überschreibt die GetHashCode‑Methode |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


Erstellt eine VCard-Instanz mit Standardwerten.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


Liest oder setzt den WiFi‑SSID‑Namen.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


Liest oder setzt den WiFi‑SSID‑Namen.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Liest oder setzt das WiFi‑Passwort.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Liest oder setzt das WiFi‑Passwort.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


Liest oder setzt die WiFi‑Verschlüsselung [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


Liest oder setzt die WiFi‑Verschlüsselung [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Liest oder setzt, ob das WiFi eine versteckte SSID ist.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Liest oder setzt, ob das WiFi eine versteckte SSID ist.


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Überschreibt die Equals‑Methode, um VCard‑Eigenschaften zu vergleichen


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | obj | java.lang.Object | VCard-Objekt zum Vergleich. |
|

**Returns:**
boolean – Gibt true zurück, wenn das übergebene VCard-Objekt denselben Typ hat und alle seine Eigenschaften den Eigenschaften dieser Instanz entsprechen.

### hashCode() {#hashCode--}
```
public int hashCode()
```


Überschreibt die GetHashCode‑Methode


**Returns:**
int – VCard-Hashcode

