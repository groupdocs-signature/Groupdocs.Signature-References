---
title: "WordProcessingSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "वर्ड प्रोसेसिंग दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

वर्ड प्रोसेसिंग दस्तावेज़ों के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | डिफ़ॉल्ट मानों के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


डिफ़ॉल्ट मानों के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | सही फ़ाइल को उसी फ़ाइल के साथ ओवरराइट करना है या नहीं, यह फ़्लैग। |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ WordProcessingSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण


**Returns:**
java.lang.String -
