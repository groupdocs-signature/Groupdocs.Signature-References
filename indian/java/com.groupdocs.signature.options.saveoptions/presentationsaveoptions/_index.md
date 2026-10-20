---
title: "PresentationSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "प्रेजेंटेशन दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

प्रेजेंटेशन दस्तावेज़ों के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | डिफ़ॉल्ट मानों के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | निर्दिष्ट आउटपुट फ़ाइल प्रारूप के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ PresentationSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ के फ़ाइल प्रारूप को प्राप्त करता है या सेट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


डिफ़ॉल्ट मानों के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


निर्दिष्ट आउटपुट फ़ाइल प्रारूप के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ PresentationSaveOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | सही फ़ाइल को उसी फ़ाइल के साथ ओवरराइट करना है या नहीं, यह फ़्लैग। |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ PresentationSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल प्रकार [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
