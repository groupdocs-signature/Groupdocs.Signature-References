---
title: "TextVerifyOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | डिफ़ॉल्ट मानों के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | सत्यापन टेक्स्ट के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | सत्यापित करने के लिए टेक्स्ट प्रॉपर्टी और हस्ताक्षर कार्यान्वयन के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getText()](#getText--) | यदि सत्यापित किया जाना चाहिए तो हस्ताक्षर टेक्स्ट निर्दिष्ट करें। |
|
|  | [setText(String value)](#setText-java.lang.String-) | यदि सत्यापित किया जाना चाहिए तो हस्ताक्षर टेक्स्ट निर्दिष्ट करें। |
|
|  | [getMatchType()](#getMatchType--) | टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
|
|  | [setMatchType(int value)](#setMatchType-int-) | टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | सत्यापित किए जाने वाले हस्ताक्षर का प्रकार। |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | सत्यापित किए जाने वाले हस्ताक्षर का प्रकार। |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | फ़ॉर्म फ़ील्ड के प्रकार को प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | फ़ॉर्म फ़ील्ड के प्रकार को प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
|
|  | [getSignatureID()](#getSignatureID--) | यदि सत्यापित किया जाना चाहिए तो टेक्स्ट सिग्नेचर आईडी को शून्य से अधिक निर्दिष्ट करें। |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | यदि सत्यापित किया जाना चाहिए तो टेक्स्ट सिग्नेचर आईडी को शून्य से अधिक निर्दिष्ट करें। |
|
|  | [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है।


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


सत्यापन टेक्स्ट के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | सत्यापित करने के लिए टेक्स्ट |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


सत्यापित करने के लिए टेक्स्ट प्रॉपर्टी और हस्ताक्षर कार्यान्वयन के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | पाठ | java.lang.String | सत्यापित करने के लिए टेक्स्ट। |
|
|  | कार्यान्वयन | int | सिग्नेचर कार्यान्वयन प्रकार। |
|

### getText() {#getText--}
```
public final String getText()
```


यदि सत्यापित किया जाना चाहिए तो हस्ताक्षर टेक्स्ट निर्दिष्ट करें।


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


यदि सत्यापित किया जाना चाहिए तो हस्ताक्षर टेक्स्ट निर्दिष्ट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


सत्यापित किए जाने वाले हस्ताक्षर का प्रकार।


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


सत्यापित किए जाने वाले हस्ताक्षर का प्रकार।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके।
यदि यह प्रॉपर्टी सेट की गई है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके।
यदि यह प्रॉपर्टी सेट की गई है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


फ़ॉर्म फ़ील्ड के प्रकार को प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके।
यदि यह प्रॉपर्टी सेट की गई है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


फ़ॉर्म फ़ील्ड के प्रकार को प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके।
यदि यह प्रॉपर्टी सेट की गई है, तो टेक्स्ट केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


यदि सत्यापित किया जाना चाहिए तो टेक्स्ट सिग्नेचर आईडी को शून्य से अधिक निर्दिष्ट करें। यह प्रॉपर्टी केवल PDF दस्तावेज़ों के लिए समर्थित है।


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


यदि सत्यापित किया जाना चाहिए तो टेक्स्ट सिग्नेचर आईडी को शून्य से अधिक निर्दिष्ट करें। यह प्रॉपर्टी केवल PDF दस्तावेज़ों के लिए समर्थित है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।


**Returns:**
java.lang.String -
