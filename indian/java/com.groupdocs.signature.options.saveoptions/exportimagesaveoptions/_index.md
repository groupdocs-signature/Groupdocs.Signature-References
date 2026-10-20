---
title: "ExportImageSaveOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ों को इमेज में निर्यात करने के लिए सहेजने विकल्प।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

दस्तावेज़ों को इमेज में निर्यात करने के लिए सहेजने विकल्प।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | डिफ़ॉल्ट मानों के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | निर्यात के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है। |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | निर्यात के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है। |
|
|  | [getExportAllPages()](#getExportAllPages--) | प्रत्येक पृष्ठ को निर्यात करने के लिए फ़्लैग। |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | प्रत्येक पृष्ठ को निर्यात करने के लिए फ़्लैग। |
|
|  | [getPagesSetup()](#getPagesSetup--) | साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
|
|  | [getPageColumns()](#getPageColumns--) | निर्यातित छवियों के लिए कॉलम की संख्या प्राप्त या सेट करता है। |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | निर्यातित छवियों के लिए कॉलम की संख्या प्राप्त या सेट करता है। |
|
|  | [getBorder()](#getBorder--) | छवि बॉर्डर सेटिंग्स प्राप्त या सेट करता है। |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | छवि बॉर्डर सेटिंग्स प्राप्त या सेट करता है। |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Tiff छवि में विभिन्न फ्रेमों पर दस्तावेज़ पृष्ठ रखें। |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Tiff छवि में विभिन्न फ्रेमों पर दस्तावेज़ पृष्ठ रखें। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


डिफ़ॉल्ट मानों के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | fileFormat | int | आउटपुट छवि फ़ाइल प्रारूप। |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


निर्यात के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है।
न्यूनतम मान 1 है।


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


निर्यात के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त या सेट करता है।
न्यूनतम मान 1 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


प्रत्येक पृष्ठ को निर्यात करने के लिए फ़्लैग।


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


प्रत्येक पृष्ठ को निर्यात करने के लिए फ़्लैग।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प।


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


निर्यातित छवियों के लिए कॉलम की संख्या प्राप्त या सेट करता है।
यदि आपको छवियों को एक पंक्ति में रखना है तो इस प्रॉपर्टी का उपयोग करें।


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


निर्यातित छवियों के लिए कॉलम की संख्या प्राप्त या सेट करता है।
यदि आपको छवियों को एक पंक्ति में रखना है तो इस प्रॉपर्टी का उपयोग करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


छवि बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से यह मान सेट नहीं होता है।


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


छवि बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से यह मान सेट नहीं होता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Tiff छवि में विभिन्न फ्रेमों पर दस्तावेज़ पृष्ठ रखें।


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Tiff छवि में विभिन्न फ्रेमों पर दस्तावेज़ पृष्ठ रखें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
