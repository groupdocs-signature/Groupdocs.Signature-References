---
title: "WiFi"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "WiFi नेटवर्क कनेक्शन विवरण का प्रतिनिधित्व करता है।"
type: docs
weight: 20
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

WiFi नेटवर्क कनेक्शन विवरण का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WiFi()](#WiFi--) | डिफ़ॉल्ट मानों के साथ VCard इंस्टेंस बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSSID()](#getSSID--) | WiFi SSID नाम को प्राप्त करता है या सेट करता है। |
| [setSSID(String value)](#setSSID-java.lang.String-) | WiFi SSID नाम को प्राप्त करता है या सेट करता है। |
| [getPassword()](#getPassword--) | WiFi पासवर्ड को प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | WiFi पासवर्ड को प्राप्त करता है या सेट करता है। |
| [getEncryption()](#getEncryption--) | WiFi एन्क्रिप्शन को प्राप्त करता है या सेट करता है [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)। |
| [setEncryption(int value)](#setEncryption-int-) | WiFi एन्क्रिप्शन को प्राप्त करता है या सेट करता है [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)। |
| [getHidden()](#getHidden--) | यदि WiFi छिपा हुआ SSID है तो उसे प्राप्त करता है या सेट करता है। |
| [setHidden(boolean value)](#setHidden-boolean-) | यदि WiFi छिपा हुआ SSID है तो उसे प्राप्त करता है या सेट करता है। |
| [equals(Object obj)](#equals-java.lang.Object-) | VCard गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
### WiFi() {#WiFi--}
```
public WiFi()
```


डिफ़ॉल्ट मानों के साथ VCard इंस्टेंस बनाता है।

### getSSID() {#getSSID--}
```
public final String getSSID()
```


WiFi SSID नाम को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


WiFi SSID नाम को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


WiFi पासवर्ड को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


WiFi पासवर्ड को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


WiFi एन्क्रिप्शन को प्राप्त करता है या सेट करता है [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)।

**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


WiFi एन्क्रिप्शन को प्राप्त करता है या सेट करता है [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype)।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


यदि WiFi छिपा हुआ SSID है तो उसे प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


यदि WiFi छिपा हुआ SSID है तो उसे प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


VCard गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| obj | java.lang.Object | तुलना करने के लिए VCard ऑब्जेक्ट। |

**Returns:**
boolean - यदि पास किया गया VCard ऑब्जेक्ट समान प्रकार का है और उसकी सभी प्रॉपर्टीज़ इस इंस्टेंस की प्रॉपर्टीज़ के बराबर हैं तो true लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है।

**Returns:**
int - VCard हैश कोड
