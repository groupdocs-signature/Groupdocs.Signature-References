---
title: "SignOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "हस्ताक्षर विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 16
url: /hi/java/com.groupdocs.signature.options.sign/signoptions/
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
|  | [getPageNumber()](#getPageNumber--) | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है। |
|
|  | [getAllPages()](#getAllPages--) | सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर रखें। |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर रखें। |
|
|  | [getAppearance()](#getAppearance--) | अतिरिक्त हस्ताक्षर रूप। |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | अतिरिक्त हस्ताक्षर रूप। |
|
|  | [getExtensions()](#getExtensions--) | हस्ताक्षर एक्सटेंशन। |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | हस्ताक्षर एक्सटेंशन। |
|
|  | [getPagesSetup()](#getPagesSetup--) | साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प। |
|
|  | [getSignatureType()](#getSignatureType--) | हस्ताक्षर प्रकार प्राप्त करें [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | हस्ताक्षर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | हस्ताक्षर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है। |
|
|  | [setZOrder(int value)](#setZOrder-int-) | टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है। |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है। |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है। |
|
|  | [toString()](#toString--) | ओवरराइड स्ट्रिंग रूपांतरण। |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है।
न्यूनतम और डिफ़ॉल्ट मान 1 है।


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


हस्ताक्षर के लिए दस्तावेज़ पृष्ठ संख्या प्राप्त करता है या सेट करता है।
न्यूनतम और डिफ़ॉल्ट मान 1 है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर रखें।


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


सभी दस्तावेज़ पृष्ठों पर हस्ताक्षर रखें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


अतिरिक्त हस्ताक्षर रूप।


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


अतिरिक्त हस्ताक्षर रूप।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


हस्ताक्षर एक्सटेंशन।


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


हस्ताक्षर एक्सटेंशन।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प।


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


साइन किए जाने वाले पृष्ठों को निर्दिष्ट करने के विकल्प।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


हस्ताक्षर प्रकार प्राप्त करें [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


हस्ताक्षर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


हस्ताक्षर विकल्पों के दस्तावेज़ प्रकार को प्राप्त करें या सेट करें [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है।
ओवरलैपिंग हस्ताक्षरों के प्रदर्शन क्रम को निर्धारित करता है।


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


टेक्स्ट हस्ताक्षर की Z-ऑर्डर स्थिति प्राप्त करता है या सेट करता है।
ओवरलैपिंग हस्ताक्षरों के प्रदर्शन क्रम को निर्धारित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है।
PDF फ़ाइलों में डिजिटल हस्ताक्षरों के लिए विशेष रूप से समर्थित है।
मान [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm) पर स्थिरांक में से एक है।


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


क्रिप्टोग्राफिक ऑपरेशनों के लिए उपयोग किए जाने वाले हैश एल्गोरिदम को प्राप्त करता है या सेट करता है।
PDF फ़ाइलों में डिजिटल हस्ताक्षरों के लिए विशेष रूप से समर्थित है।


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
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
