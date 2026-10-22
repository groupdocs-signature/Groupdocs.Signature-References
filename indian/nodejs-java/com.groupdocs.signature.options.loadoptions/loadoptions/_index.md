---
title: "LoadOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ को साइन करने के लिए खोलते समय पासवर्ड जैसी अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.options.loadoptions/loadoptions/
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
| [LoadOptions()](#LoadOptions--) | LoadOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPassword()](#getPassword--) | संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
| [getLoadExternalResources()](#getLoadExternalResources--) | बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं, यह निर्दिष्ट करने वाले विकल्प प्राप्त करता है या सेट करता है। |
| [setLoadExternalResources(boolean value)](#setLoadExternalResources-boolean-) | बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं, यह निर्दिष्ट करने वाले विकल्प प्राप्त करता है या सेट करता है। |
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

### getPassword() {#getPassword--}
```
public final String getPassword()
```


संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। यह साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए भी उपयोग किया जाएगा।

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


संरक्षित दस्तावेज़ खोलने के लिए पासवर्ड प्राप्त करता है या सेट करता है। यह साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए भी उपयोग किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLoadExternalResources() {#getLoadExternalResources--}
```
public final boolean getLoadExternalResources()
```


बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं, यह निर्दिष्ट करने वाले विकल्प प्राप्त करता है या सेट करता है। इस विकल्प को निष्क्रिय (false) करने से कई या बड़े बाहरी संसाधन लिंक वाले दस्तावेज़ों के लोडिंग समय को बचाया जा सकता है। डिफ़ॉल्ट रूप से यह विकल्प सक्रिय (true) रहता है।

**Returns:**
boolean
### setLoadExternalResources(boolean value) {#setLoadExternalResources-boolean-}
```
public final void setLoadExternalResources(boolean value)
```


बाहरी दस्तावेज़ संसाधनों को लोड किया जाना चाहिए या नहीं, यह निर्दिष्ट करने वाले विकल्प प्राप्त करता है या सेट करता है। इस विकल्प को निष्क्रिय (false) करने से कई या बड़े बाहरी संसाधन लिंक वाले दस्तावेज़ों के लोडिंग समय को बचाया जा सकता है। डिफ़ॉल्ट रूप से यह विकल्प सक्रिय (true) रहता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

