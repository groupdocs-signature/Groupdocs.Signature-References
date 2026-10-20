---
title: "वाईफ़ाई"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "WiFi नेटवर्क कनेक्शन विवरण का प्रतिनिधित्व करता है।"
type: docs
weight: 20
url: /hi/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
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
|  | [WiFi()](#WiFi--) | डिफ़ॉल्ट मानों के साथ VCard इंस्टेंस बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSSID()](#getSSID--) | वाईफ़ाई SSID नाम प्राप्त करता है या सेट करता है। |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | वाईफ़ाई SSID नाम प्राप्त करता है या सेट करता है। |
|
|  | [getPassword()](#getPassword--) | वाईफ़ाई पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | वाईफ़ाई पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [getEncryption()](#getEncryption--) | वाईफ़ाई एन्क्रिप्शन [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype) प्राप्त करता है या सेट करता है। |
|
|  | [setEncryption(int value)](#setEncryption-int-) | वाईफ़ाई एन्क्रिप्शन [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype) प्राप्त करता है या सेट करता है। |
|
|  | [getHidden()](#getHidden--) | यदि वाईफ़ाई छिपा हुआ SSID है तो प्राप्त करता है या सेट करता है। |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | यदि वाईफ़ाई छिपा हुआ SSID है तो प्राप्त करता है या सेट करता है। |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | VCard गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


डिफ़ॉल्ट मानों के साथ VCard इंस्टेंस बनाता है।


### getSSID() {#getSSID--}
```
public final String getSSID()
```


वाईफ़ाई SSID नाम प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


वाईफ़ाई SSID नाम प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


वाईफ़ाई पासवर्ड प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


वाईफ़ाई पासवर्ड प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


वाईफ़ाई एन्क्रिप्शन [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype) प्राप्त करता है या सेट करता है।


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


वाईफ़ाई एन्क्रिप्शन [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype) प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


यदि वाईफ़ाई छिपा हुआ SSID है तो प्राप्त करता है या सेट करता है।


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


यदि वाईफ़ाई छिपा हुआ SSID है तो प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


VCard गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | ऑब्जेक्ट | java.lang.Object | तुलना करने के लिए VCard ऑब्जेक्ट। |
|

**Returns:**
boolean - यदि पास किया गया VCard ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस के गुणों के बराबर हैं तो true लौटाता है।

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है


**Returns:**
int - VCard हैश कोड

