---
title: "SignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getPageNumber()](#getPageNumber--) | साइनिंग के लिए दस्तावेज़ पृष्ठ संख्या को प्राप्त करता है या सेट करता है। |
| [setPageNumber(int value)](#setPageNumber-int-) | साइनिंग के लिए दस्तावेज़ पृष्ठ संख्या को प्राप्त करता है या सेट करता है। |
| [getAllPages()](#getAllPages--) | सभी दस्तावेज़ पृष्ठों पर सिग्नेचर रखें। |
| [setAllPages(boolean value)](#setAllPages-boolean-) | सभी दस्तावेज़ पृष्ठों पर सिग्नेचर रखें। |
| [getAppearance()](#getAppearance--) | अतिरिक्त सिग्नेचर रूप। |
| [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | अतिरिक्त सिग्नेचर रूप। |
| [getExtensions()](#getExtensions--) | सिग्नेचर एक्सटेंशन। |
| [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | सिग्नेचर एक्सटेंशन। |
| [getPagesSetup()](#getPagesSetup--) | साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प। |
| [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प। |
| [getSignatureType()](#getSignatureType--) | सिग्नेचर प्रकार प्राप्त करें [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
| [getDocumentType()](#getDocumentType--) | सिग्नेचर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [setDocumentType(int value)](#setDocumentType-int-) | सिग्नेचर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
| [getZOrder()](#getZOrder--) | टेक्स्ट सिग्नेचर की Z-ऑर्डर स्थिति को प्राप्त करता है या सेट करता है। |
| [setZOrder(int value)](#setZOrder-int-) | टेक्स्ट सिग्नेचर की Z-ऑर्डर स्थिति को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


साइनिंग के लिए दस्तावेज़ पृष्ठ संख्या को प्राप्त करता है या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1 है।

**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


साइनिंग के लिए दस्तावेज़ पृष्ठ संख्या को प्राप्त करता है या सेट करता है। न्यूनतम और डिफ़ॉल्ट मान 1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


सभी दस्तावेज़ पृष्ठों पर सिग्नेचर रखें।

**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


सभी दस्तावेज़ पृष्ठों पर सिग्नेचर रखें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


अतिरिक्त सिग्नेचर रूप।

**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


अतिरिक्त सिग्नेचर रूप।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


सिग्नेचर एक्सटेंशन।

**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


सिग्नेचर एक्सटेंशन।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प।

**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


साइन किए जाने वाले पेजों को निर्दिष्ट करने के विकल्प।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


सिग्नेचर प्रकार प्राप्त करें [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)

**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


सिग्नेचर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


सिग्नेचर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


टेक्स्ट सिग्नेचर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है। ओवरलैपिंग सिग्नेचर की डिस्प्ले क्रम निर्धारित करता है।

**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


टेक्स्ट सिग्नेचर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है। ओवरलैपिंग सिग्नेचर की डिस्प्ले क्रम निर्धारित करता है।

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
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
