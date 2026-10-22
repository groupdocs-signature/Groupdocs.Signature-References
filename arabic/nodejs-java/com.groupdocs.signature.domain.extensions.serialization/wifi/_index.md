---
title: "WiFi"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يمثل تفاصيل اتصال شبكة WiFi."
type: docs
weight: 20
url: /ar/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

يمثل تفاصيل اتصال شبكة WiFi.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [WiFi()](#WiFi--) | ينشئ كائن VCard بالقيم الافتراضية. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSSID()](#getSSID--) | الحصول أو تعيين اسم SSID للواي فاي. |
| [setSSID(String value)](#setSSID-java.lang.String-) | الحصول أو تعيين اسم SSID للواي فاي. |
| [getPassword()](#getPassword--) | الحصول أو تعيين كلمة مرور الواي فاي. |
| [setPassword(String value)](#setPassword-java.lang.String-) | الحصول أو تعيين كلمة مرور الواي فاي. |
| [getEncryption()](#getEncryption--) | الحصول أو تعيين تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [setEncryption(int value)](#setEncryption-int-) | الحصول أو تعيين تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
| [getHidden()](#getHidden--) | الحصول أو تعيين ما إذا كان الواي فاي يحتوي على SSID مخفي. |
| [setHidden(boolean value)](#setHidden-boolean-) | الحصول أو تعيين ما إذا كان الواي فاي يحتوي على SSID مخفي. |
| [equals(Object obj)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص VCard |
| [hashCode()](#hashCode--) | يتجاوز طريقة GetHashCode |
### WiFi() {#WiFi--}
```
public WiFi()
```


ينشئ كائن VCard بالقيم الافتراضية.

### getSSID() {#getSSID--}
```
public final String getSSID()
```


الحصول أو تعيين اسم SSID للواي فاي.

**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


الحصول أو تعيين اسم SSID للواي فاي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


الحصول أو تعيين كلمة مرور الواي فاي.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


الحصول أو تعيين كلمة مرور الواي فاي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


الحصول أو تعيين تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


الحصول أو تعيين تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


الحصول أو تعيين ما إذا كان الواي فاي يحتوي على SSID مخفي.

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


الحصول أو تعيين ما إذا كان الواي فاي يحتوي على SSID مخفي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


يستبدل طريقة Equals لمقارنة خصائص VCard

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | كائن VCard للمقارنة معه. |

**Returns:**
boolean - يرجع true إذا كان كائن VCard الممرّر له نفس النوع وجميع خصائصه مساوية لخصائص هذا الكائن.
### hashCode() {#hashCode--}
```
public int hashCode()
```


يتجاوز طريقة GetHashCode

**Returns:**
int - رمز تجزئة VCard
