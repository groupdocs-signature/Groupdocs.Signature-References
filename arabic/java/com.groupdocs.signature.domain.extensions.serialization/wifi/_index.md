---
title: "واي فاي"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل تفاصيل اتصال شبكة WiFi."
type: docs
weight: 20
url: /ar/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

يمثل تفاصيل اتصال شبكة WiFi.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [WiFi()](#WiFi--) | ينشئ كائن VCard بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSSID()](#getSSID--) | يحصل أو يعيّن اسم SSID للواي فاي. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | يحصل أو يعيّن اسم SSID للواي فاي. |
|
|  | [getPassword()](#getPassword--) | يحصل أو يعيّن كلمة مرور الواي فاي. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | يحصل أو يعيّن كلمة مرور الواي فاي. |
|
|  | [getEncryption()](#getEncryption--) | يحصل أو يعيّن تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | يحصل أو يعيّن تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | يحصل أو يعيّن ما إذا كان الواي فاي SSID مخفيًا. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | يحصل أو يعيّن ما إذا كان الواي فاي SSID مخفيًا. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | يستبدل طريقة Equals لمقارنة خصائص VCard |
|
|  | [hashCode()](#hashCode--) | يستبدل طريقة GetHashCode |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


ينشئ كائن VCard بالقيم الافتراضية.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


يحصل أو يعيّن اسم SSID للواي فاي.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


يحصل أو يعيّن اسم SSID للواي فاي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


يحصل أو يعيّن كلمة مرور الواي فاي.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


يحصل أو يعيّن كلمة مرور الواي فاي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


يحصل أو يعيّن تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


يحصل أو يعيّن تشفير الواي فاي [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


يحصل أو يعيّن ما إذا كان الواي فاي SSID مخفيًا.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


يحصل أو يعيّن ما إذا كان الواي فاي SSID مخفيًا.


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
|  | obj | java.lang.Object | كائن VCard للمقارنة معه. |
|

**Returns:**
منطقية - تُرجع true إذا كان كائن VCard الممرّر من نفس النوع وجميع خصائصه مساوية لخصائص هذه الحالة.

### hashCode() {#hashCode--}
```
public int hashCode()
```


يستبدل طريقة GetHashCode


**Returns:**
int - رمز التجزئة لـ VCard

