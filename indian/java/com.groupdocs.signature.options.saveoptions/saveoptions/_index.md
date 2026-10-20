---
title: "SaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ को साइन करने के लिए सहेजते समय पासवर्ड जैसे अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 13
url: /hi/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

हस्ताक्षर के लिए दस्तावेज़ सहेजते समय अतिरिक्त विकल्प (जैसे पासवर्ड) निर्दिष्ट करने की अनुमति देता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | डिफ़ॉल्ट मानों के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है। |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है। |
|
|  | [getPassword()](#getPassword--) | पासवर्ड सुरक्षा के साथ साइन किए गए दस्तावेज़ को सहेजने के लिए पासवर्ड प्राप्त या सेट करता है। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | पासवर्ड सुरक्षा के साथ साइन किए गए दस्तावेज़ को सहेजने के लिए पासवर्ड प्राप्त या सेट करता है। |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | सुरक्षित रूप से साइन किए गए दस्तावेज़ को सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त या सेट करता है। |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | सुरक्षित रूप से साइन किए गए दस्तावेज़ को सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त या सेट करता है। |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | जब आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध हो तो उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त या सेट करता है। |
डिफ़ॉल्ट मान false है।
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | जब आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध हो तो उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त या सेट करता है। |
डिफ़ॉल्ट मान false है।
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


डिफ़ॉल्ट मानों के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | सही फ़ाइल को उसी फ़ाइल के साथ ओवरराइट करना है या नहीं, यह फ़्लैग। |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है।
अन्यथा नई फ़ाइल को संख्या के साथ प्रत्यय के रूप में बनाया जाएगा।


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है।
अन्यथा नई फ़ाइल को संख्या के साथ प्रत्यय के रूप में बनाया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


पासवर्ड सुरक्षा के साथ साइन किए गए दस्तावेज़ को सहेजने के लिए पासवर्ड प्राप्त या सेट करता है।
यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


पासवर्ड सुरक्षा के साथ साइन किए गए दस्तावेज़ को सहेजने के लिए पासवर्ड प्राप्त या सेट करता है।
यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


सुरक्षित रूप से साइन किए गए दस्तावेज़ को सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त या सेट करता है।
डिफ़ॉल्ट मान true है।
यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


सुरक्षित रूप से साइन किए गए दस्तावेज़ को सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त या सेट करता है।
डिफ़ॉल्ट मान true है।
यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


जब आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध हो तो उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त या सेट करता है।
डिफ़ॉल्ट मान false है।


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


जब आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध हो तो उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त या सेट करता है।
डिफ़ॉल्ट मान false है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

