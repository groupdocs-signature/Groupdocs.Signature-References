---
title: "WiFi"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "WiFi ağ bağlantısı ayrıntılarını temsil eder."
type: docs
weight: 20
url: /tr/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

WiFi ağ bağlantısı ayrıntılarını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WiFi()](#WiFi--) | Varsayılan değerlerle VCard örneği oluşturur. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSSID()](#getSSID--) | WiFi SSID adını alır veya ayarlar. |
| [setSSID(String value)](#setSSID-java.lang.String-) | WiFi SSID adını alır veya ayarlar. |
| [getPassword()](#getPassword--) | WiFi şifresini alır veya ayarlar. |
| [setPassword(String value)](#setPassword-java.lang.String-) | WiFi şifresini alır veya ayarlar. |
| [getEncryption()](#getEncryption--) | WiFi şifrelemesini alır veya ayarlar [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [setEncryption(int value)](#setEncryption-int-) | WiFi şifrelemesini alır veya ayarlar [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [getHidden()](#getHidden--) | WiFi gizli SSID mi olduğunu alır veya ayarlar. |
| [setHidden(boolean value)](#setHidden-boolean-) | WiFi gizli SSID mi olduğunu alır veya ayarlar. |
| [equals(Object obj)](#equals-java.lang.Object-) | VCard özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar. |
| [hashCode()](#hashCode--) | GetHashCode metodunu geçersiz kılar. |
### WiFi() {#WiFi--}
```
public WiFi()
```


Varsayılan değerlerle VCard örneği oluşturur.

### getSSID() {#getSSID--}
```
public final String getSSID()
```


WiFi SSID adını alır veya ayarlar.

**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


WiFi SSID adını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


WiFi şifresini alır veya ayarlar.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


WiFi şifresini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


WiFi şifrelemesini alır veya ayarlar [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


WiFi şifrelemesini alır veya ayarlar [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


WiFi gizli SSID mi olduğunu alır veya ayarlar.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


WiFi gizli SSID mi olduğunu alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


VCard özelliklerini karşılaştırmak için Equals metodunu geçersiz kılar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| obj | java.lang.Object | Karşılaştırılacak VCard nesnesi. |

**Returns:**
boolean - Geçilen VCard nesnesi aynı türe sahipse ve tüm özellikleri bu örnek özelliklerine eşitse true döndürür.
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode metodunu geçersiz kılar.

**Returns:**
int - VCard karma kodu
