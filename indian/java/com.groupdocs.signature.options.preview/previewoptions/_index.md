---
title: "PreviewOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ पूर्वावलोकन विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

दस्तावेज़ पूर्वावलोकन विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getWidth()](#getWidth--) | प्रीव्यू इमेज की चौड़ाई प्राप्त करता है या सेट करता है। |
|
|  | [setWidth(int value)](#setWidth-int-) | प्रीव्यू इमेज की चौड़ाई प्राप्त करता है या सेट करता है। |
|
|  | [getHeight()](#getHeight--) | प्रीव्यू इमेज की ऊँचाई प्राप्त करता है या सेट करता है। |
|
|  | [setHeight(int value)](#setHeight-int-) | प्रीव्यू इमेज की ऊँचाई प्राप्त करता है या सेट करता है। |
|
|  | [getPageNumbers()](#getPageNumbers--) | प्रीव्यू इमेज के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है। |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | प्रीव्यू इमेज के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है। |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है। |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है। |
|
|  | [getHideSignatures()](#getHideSignatures--) | पृष्ठ प्रीव्यू इमेज से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | पृष्ठ प्रीव्यू इमेज से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
|
|  | [getResolution()](#getResolution--) | प्रीव्यू इमेज की रिज़ॉल्यूशन DPI (डॉट्स पर इंच) में प्राप्त करता है। |
|
|  | [setResolution(int value)](#setResolution-int-) | प्रीव्यू इमेज की रिज़ॉल्यूशन DPI (डॉट्स पर इंच) में सेट करता है। |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | इंटरफ़ेस जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
|
|  | pageNumbers | int[] | वांछित पृष्ठ संख्याएँ |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | इंटरफ़ेस जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | आउटपुट फ़ाइल का पथ। |
|
|  | pageNumbers | int[] | वांछित पृष्ठ संख्याएँ |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


प्रीव्यू इमेज की चौड़ाई प्राप्त करता है या सेट करता है।


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


प्रीव्यू इमेज की चौड़ाई प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


प्रीव्यू इमेज की ऊँचाई प्राप्त करता है या सेट करता है।


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


प्रीव्यू इमेज की ऊँचाई प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


प्रीव्यू इमेज के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है।


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


प्रीव्यू इमेज के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


पूर्वावलोकन छवियों के स्वरूप को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


पृष्ठ प्रीव्यू इमेज से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
केवल हस्ताक्षर जिन्हें IsSignature के रूप में चिह्नित किया गया है, उत्पन्न दस्तावेज़ पृष्ठ छवि से छिपा दिया जाएगा।


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


पृष्ठ प्रीव्यू इमेज से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है।
केवल हस्ताक्षर जिन्हें IsSignature के रूप में चिह्नित किया गया है, उत्पन्न दस्तावेज़ पृष्ठ छवि से छिपा दिया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


प्रीव्यू इमेज की रिज़ॉल्यूशन DPI (डॉट्स पर इंच) में प्राप्त करता है।


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


प्रीव्यू इमेज की रिज़ॉल्यूशन DPI (डॉट्स पर इंच) में सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

