---
title: "PdfSaveOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "PDF दस्तावेज़ों के लिए सहेजने विकल्प।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
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
| [PdfSaveOptions()](#PdfSaveOptions--) | PdfSaveOptions क्लास का नया उदाहरण डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है। |
| [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | PdfSaveOptions क्लास का नया उदाहरण निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट के साथ इनिशियलाइज़ करता है। |
| [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | PdfSaveOptions क्लास का नया उदाहरण ओवरराइट फ़्लैग के साथ इनिशियलाइज़ करता है। |
| [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | PdfSaveOptions क्लास का नया उदाहरण निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है। |
| [setFileFormat(int value)](#setFileFormat-int-) | हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


PdfSaveOptions क्लास का नया उदाहरण डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है।

### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


PdfSaveOptions क्लास का नया उदाहरण निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileFormat | int | आउटपुट फ़ाइल प्रकार [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)। |

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


PdfSaveOptions क्लास का नया उदाहरण ओवरराइट फ़्लैग के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| overwriteExistingFile | boolean | साइन किए गए फ़ाइल को समान फ़ाइल से ओवरराइट करने के लिए फ़्लैग। |

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PdfSaveOptions क्लास का नया उदाहरण निर्दिष्ट आउटपुट फ़ाइल फ़ॉर्मेट और ओवरराइट फ़्लैग के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileFormat | int | आउटपुट फ़ाइल प्रकार [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)। |
| overwriteExistingFile | boolean | साइन किए गए फ़ाइल को समान फ़ाइल से ओवरराइट करने के लिए फ़्लैग। |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है।

**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


हस्ताक्षरित दस्तावेज़ का फ़ाइल फ़ॉर्मेट प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
