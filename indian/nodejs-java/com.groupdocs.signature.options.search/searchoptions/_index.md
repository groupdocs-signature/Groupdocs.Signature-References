---
title: "SearchOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ से हस्ताक्षरों को निकालने के विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 17
url: /hi/nodejs-java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

दस्तावेज़ से हस्ताक्षरों को निकालने के विकल्पों का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | खोज के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | खोज के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। |
| [getPagesSetup()](#getPagesSetup--) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प। |
| [getAllPages()](#getAllPages--) | प्रत्येक दस्तावेज़ पृष्ठ पर खोज करने के लिए फ़्लैग। |
| [setAllPages(boolean value)](#setAllPages-boolean-) | प्रत्येक दस्तावेज़ पृष्ठ पर खोज करने के लिए फ़्लैग। |
| [getSkipExternal()](#getSkipExternal--) | केवल उन हस्ताक्षरों को लौटाने के लिए फ़्लैग जो IsSignature के रूप में चिह्नित हैं। |
| [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | केवल उन हस्ताक्षरों को लौटाने के लिए फ़्लैग जो IsSignature के रूप में चिह्नित हैं। |
| [getSearchPages(int totalPages)](#getSearchPages-int-) | हस्ताक्षर निष्कर्षण के लिए पृष्ठों की सूची प्राप्त करने की वर्चुअल मेथड। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


खोज के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। मान वैकल्पिक है।

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


खोज के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। मान वैकल्पिक है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प।

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


हस्ताक्षर खोज के लिए पृष्ठ निर्दिष्ट करने के विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


प्रत्येक दस्तावेज़ पृष्ठ पर खोज करने के लिए फ़्लैग। डिफ़ॉल्ट रूप से यह मान true पर सेट है।

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


प्रत्येक दस्तावेज़ पृष्ठ पर खोज करने के लिए फ़्लैग। डिफ़ॉल्ट रूप से यह मान true पर सेट है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


केवल उन हस्ताक्षरों को लौटाने के लिए फ़्लैग जो IsSignature के रूप में चिह्नित हैं। डिफ़ॉल्ट रूप से मान false है, जो दर्शाता है कि सभी हस्ताक्षर लौटाए जाएँ जो निर्दिष्ट मानदंडों से मेल खाते हैं।

**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


केवल उन हस्ताक्षरों को लौटाने के लिए फ़्लैग जो IsSignature के रूप में चिह्नित हैं। डिफ़ॉल्ट रूप से मान false है, जो दर्शाता है कि सभी हस्ताक्षर लौटाए जाएँ जो निर्दिष्ट मानदंडों से मेल खाते हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


हस्ताक्षर निष्कर्षण के लिए पृष्ठों की सूची प्राप्त करने की वर्चुअल मेथड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| totalPages | int | पृष्ठों की कुल संख्या |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - पृष्ठ संख्याओं की सूची
### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
