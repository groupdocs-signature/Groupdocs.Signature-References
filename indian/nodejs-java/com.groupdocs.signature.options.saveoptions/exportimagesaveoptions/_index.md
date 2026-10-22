---
title: "ExportImageSaveOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ों को इमेज में निर्यात करने के लिए सहेजने विकल्प।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
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
| [ExportImageSaveOptions()](#ExportImageSaveOptions--) | डिफ़ॉल्ट मानों के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
| [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | एक्सपोर्ट के लिए दस्तावेज़ पेज संख्या प्राप्त करता है या सेट करता है। |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | एक्सपोर्ट के लिए दस्तावेज़ पेज संख्या प्राप्त करता है या सेट करता है। |
| [getExportAllPages()](#getExportAllPages--) | प्रत्येक पेज को एक्सपोर्ट करने के लिए फ़्लैग। |
| [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | प्रत्येक पेज को एक्सपोर्ट करने के लिए फ़्लैग। |
| [getPagesSetup()](#getPagesSetup--) | साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प। |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प। |
| [getPageColumns()](#getPageColumns--) | एक्सपोर्ट की गई इमेजों के लिए कॉलमों की संख्या प्राप्त करता है या सेट करता है। |
| [setPageColumns(int value)](#setPageColumns-int-) | एक्सपोर्ट की गई इमेजों के लिए कॉलमों की संख्या प्राप्त करता है या सेट करता है। |
| [getBorder()](#getBorder--) | इमेज बॉर्डर सेटिंग्स प्राप्त करता है या सेट करता है। |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | इमेज बॉर्डर सेटिंग्स प्राप्त करता है या सेट करता है। |
| [getTiffMultipage()](#getTiffMultipage--) | टिफ़ इमेज में दस्तावेज़ पेजों को विभिन्न फ्रेमों में रखें। |
| [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | टिफ़ इमेज में दस्तावेज़ पेजों को विभिन्न फ्रेमों में रखें। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


डिफ़ॉल्ट मानों के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट के साथ ExportAsImageSaveOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| fileFormat | int | आउटपुट इमेज फ़ाइल फ़ॉर्मेट। |

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


एक्सपोर्ट के लिए दस्तावेज़ पेज संख्या प्राप्त करता है या सेट करता है। न्यूनतम मान 1 है।

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


एक्सपोर्ट के लिए दस्तावेज़ पेज संख्या प्राप्त करता है या सेट करता है। न्यूनतम मान 1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


प्रत्येक पेज को एक्सपोर्ट करने के लिए फ़्लैग।

**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


प्रत्येक पेज को एक्सपोर्ट करने के लिए फ़्लैग।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प।

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


एक्सपोर्ट की गई इमेजों के लिए कॉलमों की संख्या प्राप्त करता है या सेट करता है। यदि आप इमेजों को एक पंक्ति में रखना चाहते हैं तो इस प्रॉपर्टी का उपयोग करें।

**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


एक्सपोर्ट की गई इमेजों के लिए कॉलमों की संख्या प्राप्त करता है या सेट करता है। यदि आप इमेजों को एक पंक्ति में रखना चाहते हैं तो इस प्रॉपर्टी का उपयोग करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


इमेज बॉर्डर सेटिंग्स प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से यह मान सेट नहीं है।

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


इमेज बॉर्डर सेटिंग्स प्राप्त करता है या सेट करता है। डिफ़ॉल्ट रूप से यह मान सेट नहीं है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


टिफ़ इमेज में दस्तावेज़ पेजों को विभिन्न फ्रेमों में रखें।

**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


टिफ़ इमेज में दस्तावेज़ पेजों को विभिन्न फ्रेमों में रखें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
