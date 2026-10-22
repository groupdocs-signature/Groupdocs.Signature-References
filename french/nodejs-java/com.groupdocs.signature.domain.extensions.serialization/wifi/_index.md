---
title: "WiFi"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Représente les détails de la connexion réseau WiFi."
type: docs
weight: 20
url: /fr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

Représente les détails de la connexion réseau WiFi.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [WiFi()](#WiFi--) | Crée une instance VCard avec les valeurs par défaut. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getSSID()](#getSSID--) | Obtient ou définit le nom SSID du WiFi. |
| [setSSID(String value)](#setSSID-java.lang.String-) | Obtient ou définit le nom SSID du WiFi. |
| [getPassword()](#getPassword--) | Obtient ou définit le mot de passe du WiFi. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Obtient ou définit le mot de passe du WiFi. |
| [getEncryption()](#getEncryption--) | Obtient ou définit le chiffrement WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [setEncryption(int value)](#setEncryption-int-) | Obtient ou définit le chiffrement WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [getHidden()](#getHidden--) | Obtient ou définit si le SSID du WiFi est masqué. |
| [setHidden(boolean value)](#setHidden-boolean-) | Obtient ou définit si le SSID du WiFi est masqué. |
| [equals(Object obj)](#equals-java.lang.Object-) | Écrase la méthode Equals pour comparer les propriétés VCard |
| [hashCode()](#hashCode--) | Remplace la méthode GetHashCode |
### WiFi() {#WiFi--}
```
public WiFi()
```


Crée une instance VCard avec les valeurs par défaut.

### getSSID() {#getSSID--}
```
public final String getSSID()
```


Obtient ou définit le nom SSID du WiFi.

**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


Obtient ou définit le nom SSID du WiFi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Obtient ou définit le mot de passe du WiFi.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Obtient ou définit le mot de passe du WiFi.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


Obtient ou définit le chiffrement WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


Obtient ou définit le chiffrement WiFi [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


Obtient ou définit si le SSID du WiFi est masqué.

**Returns:**
booléen
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


Obtient ou définit si le SSID du WiFi est masqué.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | booléen |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Écrase la méthode Equals pour comparer les propriétés VCard

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | Objet VCard à comparer. |

**Returns:**
booléen - Retourne vrai si l'objet VCard passé a le même type et que toutes ses propriétés sont égales aux propriétés de cette instance.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Remplace la méthode GetHashCode

**Returns:**
int - code de hachage VCard
