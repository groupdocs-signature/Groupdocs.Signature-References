---
title: "PdfTextAnnotationAppearance"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "PDF टेक्स्ट एनोटेशन ऑब्जेक्ट Title Subject Content की उपस्थिति का वर्णन करता है।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

PDF टेक्स्ट एनोटेशन ऑब्जेक्ट (शीर्षक, विषय, सामग्री) की उपस्थिति का वर्णन करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | PDF हस्ताक्षर txt एनोटेशन रूप दिखाने वाला ऑब्जेक्ट बनाता है। |
| [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | निर्दिष्ट मानों (title, subject, contents) के साथ PDF हस्ताक्षर txt एनोटेशन बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getContents()](#getContents--) | एनोटेशन ऑब्जेक्ट की सामग्री को प्राप्त करता है या सेट करता है। |
| [setContents(String value)](#setContents-java.lang.String-) | एनोटेशन ऑब्जेक्ट की सामग्री को प्राप्त करता है या सेट करता है। |
| [getSubject()](#getSubject--) | ऑब्जेक्ट का विवरण दर्शाने वाले Subject को प्राप्त करता है या सेट करता है। |
| [setSubject(String value)](#setSubject-java.lang.String-) | ऑब्जेक्ट का विवरण दर्शाने वाले Subject को प्राप्त करता है या सेट करता है। |
| [getTitle()](#getTitle--) | एनोटेशन ऑब्जेक्ट की शीर्षक पट्टी में प्रदर्शित होने वाले शीर्षक को प्राप्त करता है या सेट करता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | एनोटेशन ऑब्जेक्ट की शीर्षक पट्टी में प्रदर्शित होने वाले शीर्षक को प्राप्त करता है या सेट करता है। |
| [getBorder()](#getBorder--) | विभिन्न बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | विभिन्न बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है। |
| [getBorderEffect()](#getBorderEffect--) | बॉर्डर प्रभाव को प्राप्त करता है या सेट करता है। |
| [setBorderEffect(int value)](#setBorderEffect-int-) | बॉर्डर प्रभाव को प्राप्त करता है या सेट करता है। |
| [getBorderEffectIntensity()](#getBorderEffectIntensity--) | बॉर्डर प्रभाव की तीव्रता को प्राप्त करता है या सेट करता है। |
| [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | बॉर्डर प्रभाव की तीव्रता को प्राप्त करता है या सेट करता है। |
| [getHCornerRadius()](#getHCornerRadius--) | क्षैतिज कोने की त्रिज्या को प्राप्त करता है या सेट करता है। |
| [setHCornerRadius(int value)](#setHCornerRadius-int-) | क्षैतिज कोने की त्रिज्या को प्राप्त करता है या सेट करता है। |
| [getVCornerRadius()](#getVCornerRadius--) | ऊर्ध्वाधर कोने की त्रिज्या को प्राप्त करता है या सेट करता है। |
| [setVCornerRadius(int value)](#setVCornerRadius-int-) | ऊर्ध्वाधर कोने की त्रिज्या को प्राप्त करता है या सेट करता है। |
| [toString()](#toString--) | स्ट्रिंग रूपांतरण को ओवरराइड करें। |
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


PDF हस्ताक्षर txt एनोटेशन रूप दिखाने वाला ऑब्जेक्ट बनाता है।

### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


निर्दिष्ट मानों (title, subject, contents) के साथ PDF हस्ताक्षर txt एनोटेशन बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| शीर्षक | java.lang.String | शीर्षक। |
| विषय | java.lang.String | विषय। |
| सामग्री | java.lang.String | सामग्री। |

### getContents() {#getContents--}
```
public final String getContents()
```


एनोटेशन ऑब्जेक्ट की सामग्री को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


एनोटेशन ऑब्जेक्ट की सामग्री को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


ऑब्जेक्ट का विवरण दर्शाने वाले Subject को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


ऑब्जेक्ट का विवरण दर्शाने वाले Subject को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


एनोटेशन ऑब्जेक्ट की शीर्षक पट्टी में प्रदर्शित होने वाले शीर्षक को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


एनोटेशन ऑब्जेक्ट की शीर्षक पट्टी में प्रदर्शित होने वाले शीर्षक को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


विभिन्न बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है।

**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


विभिन्न बॉर्डर सेटिंग्स को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


बॉर्डर प्रभाव को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


बॉर्डर प्रभाव को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


बॉर्डर प्रभाव की तीव्रता को प्राप्त करता है या सेट करता है। मान की वैध सीमा [0..2] है।

**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


बॉर्डर प्रभाव की तीव्रता को प्राप्त करता है या सेट करता है। मान की वैध सीमा [0..2] है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


क्षैतिज कोने की त्रिज्या को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


क्षैतिज कोने की त्रिज्या को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


ऊर्ध्वाधर कोने की त्रिज्या को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


ऊर्ध्वाधर कोने की त्रिज्या को प्राप्त करता है या सेट करता है।

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
