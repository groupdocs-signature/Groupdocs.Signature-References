---
title: "VerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/verifyoptions/
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
| [isValid()](#isValid--) | वैध प्रॉपर्टी फ़्लैग। |
| [setValid(boolean value)](#setValid-boolean-) | वैध प्रॉपर्टी फ़्लैग। |
| [getPageNumber()](#getPageNumber--) | सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। |
| [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | सत्यापित किए जाने वाले दस्तावेज़ पृष्ठ संख्या। |
| [getPagesSetup()](#getPagesSetup--) | सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए Page Options। |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए Page Options। |
| [getAllPages()](#getAllPages--) | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए फ़्लैग। |
| [setAllPages(boolean value)](#setAllPages-boolean-) | प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए फ़्लैग। |
| [getExtensions()](#getExtensions--) | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त विस्तार। |
| [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त विस्तार। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


दस्तावेज़ पृष्ठ संख्या को सत्यापित किया जाना है। यदि गुण सेट नहीं है - दस्तावेज़ के सभी पृष्ठ पहली बार के लिए सत्यापित किए जाएंगे। न्यूनतम मान 1 है।

**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


दस्तावेज़ पृष्ठ संख्या को सत्यापित किया जाना है। यदि गुण सेट नहीं है - दस्तावेज़ के सभी पृष्ठ पहली बार के लिए सत्यापित किए जाएंगे। न्यूनतम मान 1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए Page Options।

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


सत्यापित किए जाने वाले पृष्ठों को निर्दिष्ट करने के लिए Page Options।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए फ़्लैग। डिफ़ॉल्ट मान true है।

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


प्रत्येक दस्तावेज़ पृष्ठ को सत्यापित करने के लिए फ़्लैग। डिफ़ॉल्ट मान true है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त विस्तार।

**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


वैकल्पिक हस्ताक्षर विकल्प सत्यापन के लिए अतिरिक्त विस्तार।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग रूपांतरण को ओवरराइड करें।

**Returns:**
java.lang.String -
