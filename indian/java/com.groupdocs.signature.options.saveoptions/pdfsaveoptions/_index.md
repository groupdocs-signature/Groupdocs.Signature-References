---
title: "PdfSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "PDF दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF दस्तावेज़ों के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | डिफ़ॉल्ट मानों के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | निर्दिष्ट आउटपुट फ़ाइल प्रारूप के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | ओवरराइट फ़्लैग के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | निर्दिष्ट आउटपुट फ़ाइल प्रारूप और ओवरराइट फ़्लैग के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | एक अनुमतियों पासवर्ड (मुख्य पासवर्ड) अनुमति सेटिंग्स को बदलने के लिए पासवर्ड की आवश्यकता होती है। |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | एक अनुमतियों पासवर्ड (मुख्य पासवर्ड) अनुमति सेटिंग्स को बदलने के लिए पासवर्ड की आवश्यकता होती है। |
|
|  | [getPermissions()](#getPermissions--) | PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


डिफ़ॉल्ट मानों के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


निर्दिष्ट आउटपुट फ़ाइल प्रारूप के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)। |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


ओवरराइट फ़्लैग के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | सही फ़ाइल को उसी फ़ाइल के साथ ओवरराइट करना है या नहीं, यह फ़्लैग। |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट फ़ाइल प्रारूप और ओवरराइट फ़्लैग के साथ PdfSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)। |
|
|  | overwriteExistingFile | boolean | सही फ़ाइल को उसी फ़ाइल के साथ ओवरराइट करना है या नहीं, यह फ़्लैग। |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


एक अनुमतियों पासवर्ड (मुख्य पासवर्ड) अनुमति सेटिंग्स को बदलने के लिए पासवर्ड की आवश्यकता होती है।


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


एक अनुमतियों पासवर्ड (मुख्य पासवर्ड) अनुमति सेटिंग्स को बदलने के लिए पासवर्ड की आवश्यकता होती है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण।


इन अनुमतियों को संशोधित करने के लिए,
PermissionsPassword
सेट होना चाहिए।
मान [Permissions](../../com.groupdocs.signature.options/permissions) से फ़्लैग संयोजन है।
एक
null
मान का अर्थ है कि कोई स्पष्ट अनुमतियाँ लागू नहीं की गई हैं।


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


PDF दस्तावेज़ की अनुमतियाँ जैसे प्रिंटिंग, संशोधन और डेटा निष्कर्षण।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
