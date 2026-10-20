---
title: "VerifyOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

दस्तावेज़ को सत्यापित करने के विकल्प रखता है।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [isValid()](#isValid--) | वैध प्रॉपर्टी फ़्लैग। |
|
|  | [setValid(boolean value)](#setValid-boolean-) | वैध प्रॉपर्टी फ़्लैग। |
|
|  | [getPageNumber()](#getPageNumber--) | सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। |
|
|  | [getPagesSetup()](#getPagesSetup--) | सत्यापन के लिए पृष्ठ निर्दिष्ट करने के पृष्ठ विकल्प। |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | सत्यापन के लिए पृष्ठ निर्दिष्ट करने के पृष्ठ विकल्प। |
|
|  | [getAllPages()](#getAllPages--) | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने का फ़्लैग। |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने का फ़्लैग। |
|
|  | [getExtensions()](#getExtensions--) | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन। |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


वैध प्रॉपर्टी फ़्लैग।


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


वैध प्रॉपर्टी फ़्लैग।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। यदि प्रॉपर्टी सेट नहीं है - सभी पृष्ठों के
दस्तावेज़ पहली घटना के लिए सत्यापित किया जाएगा।
न्यूनतम मान 1 है।


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। यदि प्रॉपर्टी सेट नहीं है - सभी पृष्ठों के
दस्तावेज़ पहली घटना के लिए सत्यापित किया जाएगा।
न्यूनतम मान 1 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


सत्यापन के लिए पृष्ठ निर्दिष्ट करने के पृष्ठ विकल्प।


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


सत्यापन के लिए पृष्ठ निर्दिष्ट करने के पृष्ठ विकल्प।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने का फ़्लैग। डिफ़ॉल्ट रूप से मान true है।


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने का फ़्लैग। डिफ़ॉल्ट रूप से मान true है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन।


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त एक्सटेंशन।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


ओवरराइड स्ट्रिंग रूपांतरण।


**Returns:**
java.lang.String -
