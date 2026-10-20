---
title: "LoadOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ को साइन करने के लिए खोलते समय पासवर्ड जैसे अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

दस्तावेज़ को साइन करने के लिए खोलते समय अतिरिक्त विकल्प (जैसे पासवर्ड) निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions वर्ग की नई इंस्टेंस को प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPassword()](#getPassword--) | संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
|
|  | [getLoadExternalResources()](#getLoadExternalResources--) | विकल्प प्राप्त करता है या सेट करता है जो यह निर्दिष्ट करता है कि बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं। |
|
|  | [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | विकल्प प्राप्त करता है या सेट करता है जो यह निर्दिष्ट करता है कि बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं। |
|
|  | [getPermissions()](#getPermissions--) | PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | आंतरिक सेट्टर, जो दस्तावेज़ लोड प्रोसेसर द्वारा फ़ाइल से पार्स की गई अनुमतियों को रिकॉर्ड करने के लिए उपयोग किया जाता है। |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions वर्ग की नई इंस्टेंस को प्रारंभ करता है।


### getPassword() {#getPassword--}
```
public final String getPassword()
```


संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है।
यह हस्ताक्षरित दस्तावेज़ को संरक्षित के रूप में सहेजने के लिए भी उपयोग किया जाएगा।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है।
यह हस्ताक्षरित दस्तावेज़ को संरक्षित के रूप में सहेजने के लिए भी उपयोग किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


विकल्प प्राप्त करता है या सेट करता है जो यह निर्दिष्ट करता है कि बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं।
यह विकल्प, जब निष्क्रिय मान (false) हो, कई या बड़े बाहरी संसाधन लिंक वाले दस्तावेज़ों के लिए लोडिंग समय बचाने की अनुमति देता है।
डिफ़ॉल्ट रूप से मान सक्रिय (true) है।


**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


विकल्प प्राप्त करता है या सेट करता है जो यह निर्दिष्ट करता है कि बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं।
यह विकल्प, जब निष्क्रिय मान (false) हो, कई या बड़े बाहरी संसाधन लिंक वाले दस्तावेज़ों के लिए लोडिंग समय बचाने की अनुमति देता है।
डिफ़ॉल्ट रूप से मान सक्रिय (true) है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण।
केवल PDF दस्तावेज़ों के लिए। केवल-पढ़ने योग्य \u2014 लोड करते समय स्वचालित रूप से भर दिया जाता है।
मान [Permissions](../../com.groupdocs.signature.options/permissions) से फ़्लैग संयोजन है।


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


आंतरिक सेट्टर, जो दस्तावेज़ लोड प्रोसेसर द्वारा फ़ाइल से पार्स की गई अनुमतियों को रिकॉर्ड करने के लिए उपयोग किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

