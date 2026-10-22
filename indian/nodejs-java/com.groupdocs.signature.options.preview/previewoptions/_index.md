---
title: "PreviewOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

दस्तावेज़ प्रीव्यू विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
| [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
| [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | PreviewOptions ऑब्जेक्ट को प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getWidth()](#getWidth--) | पूर्वावलोकन छवियों की चौड़ाई प्राप्त करता है या सेट करता है। |
| [setWidth(int value)](#setWidth-int-) | पूर्वावलोकन छवियों की चौड़ाई प्राप्त करता है या सेट करता है। |
| [getHeight()](#getHeight--) | पूर्वावलोकन छवियों की ऊँचाई प्राप्त करता है या सेट करता है। |
| [setHeight(int value)](#setHeight-int-) | पूर्वावलोकन छवियों की ऊँचाई प्राप्त करता है या सेट करता है। |
| [getPageNumbers()](#getPageNumbers--) | पूर्वावलोकन छवियों के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है। |
| [setPageNumbers(int[] value)](#setPageNumbers-int---) | पूर्वावलोकन छवियों के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है। |
| [getPreviewFormat()](#getPreviewFormat--) | पूर्वावलोकन छवियों का प्रारूप प्राप्त करता है या सेट करता है। |
| [setPreviewFormat(int value)](#setPreviewFormat-int-) | पूर्वावलोकन छवियों का प्रारूप प्राप्त करता है या सेट करता है। |
| [getHideSignatures()](#getHideSignatures--) | पृष्ठ पूर्वावलोकन छवि से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
| [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | पृष्ठ पूर्वावलोकन छवि से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। |
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | इंटरफ़ेस जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
| pageNumbers | int[] | वांछित पृष्ठ संख्याएँ |

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | इंटरफ़ेस जो आउटपुट पृष्ठ पूर्वावलोकन स्ट्रीम बनाने की विधि को परिभाषित करता है। |
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


PreviewOptions ऑब्जेक्ट को प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filePathFormat | java.lang.String | आउटपुट फ़ाइल का पथ। |
| pageNumbers | int[] | वांछित पृष्ठ संख्याएँ |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


पूर्वावलोकन छवियों की चौड़ाई प्राप्त करता है या सेट करता है।

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


पूर्वावलोकन छवियों की चौड़ाई प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


पूर्वावलोकन छवियों की ऊँचाई प्राप्त करता है या सेट करता है।

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


पूर्वावलोकन छवियों की ऊँचाई प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


पूर्वावलोकन छवियों के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है।

**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


पूर्वावलोकन छवियों के पृष्ठ संख्याएँ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


पूर्वावलोकन छवियों का प्रारूप प्राप्त करता है या सेट करता है।

**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


पूर्वावलोकन छवियों का प्रारूप प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


पृष्ठ पूर्वावलोकन छवि से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। केवल वे हस्ताक्षर जो IsSignature के रूप में चिह्नित हैं, उत्पन्न दस्तावेज़ पृष्ठ छवि से छिपाए जाएंगे।

**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


पृष्ठ पूर्वावलोकन छवि से हस्ताक्षर छिपाने के लिए फ़्लैग प्राप्त करता है या सेट करता है। केवल वे हस्ताक्षर जो IsSignature के रूप में चिह्नित हैं, उत्पन्न दस्तावेज़ पृष्ठ छवि से छिपाए जाएंगे।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

