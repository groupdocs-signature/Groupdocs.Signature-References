---
title: "SaveOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ को साइन करने के लिए सहेजते समय पासवर्ड जैसी अतिरिक्त विकल्प निर्दिष्ट करने की अनुमति देता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

हस्ताक्षर करने के लिए दस्तावेज़ सहेजते समय अतिरिक्त विकल्प (जैसे पासवर्ड) निर्दिष्ट करने की अनुमति देता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SaveOptions()](#SaveOptions--) | डिफ़ॉल्ट मानों के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
| [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ SaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है। |
| [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त या सेट करता है। |
| [getPassword()](#getPassword--) | साइन किए गए दस्तावेज़ को पासवर्ड सुरक्षा के साथ सहेजने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
| [setPassword(String value)](#setPassword-java.lang.String-) | साइन किए गए दस्तावेज़ को पासवर्ड सुरक्षा के साथ सहेजने के लिए पासवर्ड प्राप्त करता है या सेट करता है। |
| [getUseOriginalPassword()](#getUseOriginalPassword--) | साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त करता है या सेट करता है। |
| [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त करता है या सेट करता है। |
| [getAddMissingExtenstion()](#getAddMissingExtenstion--) | आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध होने पर उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है। |
| [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध होने पर उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| overwriteExistingFile | boolean | साइन किए गए फ़ाइल को समान फ़ाइल से ओवरराइट करने के लिए फ़्लैग। |

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त करता है या सेट करता है। अन्यथा नई फ़ाइल संख्या को उपसर्ग के रूप में जोड़कर बनाई जाएगी।

**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


नए आउटपुट फ़ाइल के साथ मौजूदा फ़ाइल को ओवरराइट करना है या नहीं, प्राप्त करता है या सेट करता है। अन्यथा नई फ़ाइल संख्या को उपसर्ग के रूप में जोड़कर बनाई जाएगी।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


साइन किए गए दस्तावेज़ को पासवर्ड सुरक्षा के साथ सहेजने के लिए पासवर्ड प्राप्त करता है या सेट करता है। यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


साइन किए गए दस्तावेज़ को पासवर्ड सुरक्षा के साथ सहेजने के लिए पासवर्ड प्राप्त करता है या सेट करता है। यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान true है। यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।

**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


साइन किए गए दस्तावेज़ को संरक्षित रूप में सहेजने के लिए LoadOptions से पासवर्ड का उपयोग करना है या नहीं, प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान true है। यह प्रॉपर्टी इमेज दस्तावेज़ों के लिए समर्थित नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध होने पर उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है।

**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


आउटपुट फ़ाइल पथ में एक्सटेंशन अनुपलब्ध होने पर उसे स्वचालित रूप से जोड़ने के लिए फ़्लैग प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान false है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

