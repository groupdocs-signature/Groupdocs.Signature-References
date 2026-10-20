---
title: "SpreadsheetSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "स्प्रेडशीट दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

स्प्रेडशीट दस्तावेज़ों के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | डिफ़ॉल्ट मानों के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | पूर्वनिर्धारित आउटपुट फ़ाइल फ़ॉर्मेट के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


डिफ़ॉल्ट मानों के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


पूर्वनिर्धारित आउटपुट फ़ाइल फ़ॉर्मेट के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल फ़ॉर्मेट निर्दिष्ट करता है। |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


निर्दिष्ट आउटपुट प्रकार और ओवरराइट फ़्लैग के साथ SpreadsheetSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट फ़ाइल फ़ॉर्मेट निर्दिष्ट करता है। |
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
