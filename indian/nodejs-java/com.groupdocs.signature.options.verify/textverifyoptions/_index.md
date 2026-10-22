---
title: "TextVerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

दस्तावेज़ टेक्स्ट हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

--------------------

**Learn more**

 *  Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/
[Advanced usage of eVerification Barcode signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-text-signatures/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [TextVerifyOptions()](#TextVerifyOptions--) | डिफ़ॉल्ट मानों के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है। |
| [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | सत्यापन पाठ के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है। |
| [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | सत्यापित करने के लिए Text गुण और हस्ताक्षर कार्यान्वयन के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getText()](#getText--) | यदि इसे सत्यापित किया जाना चाहिए तो हस्ताक्षर पाठ निर्दिष्ट करें। |
| [setText(String value)](#setText-java.lang.String-) | यदि इसे सत्यापित किया जाना चाहिए तो हस्ताक्षर पाठ निर्दिष्ट करें। |
| [getMatchType()](#getMatchType--) | Text Match Type सत्यापन को प्राप्त करता है या सेट करता है। |
| [setMatchType(int value)](#setMatchType-int-) | Text Match Type सत्यापन को प्राप्त करता है या सेट करता है। |
| [getSignatureImplementation()](#getSignatureImplementation--) | सत्यापित किए जाने वाले हस्ताक्षर का प्रकार। |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | सत्यापित किए जाने वाले हस्ताक्षर का प्रकार। |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
| [getFormTextFieldType()](#getFormTextFieldType--) | फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
| [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। |
| [getSignatureID()](#getSignatureID--) | यदि इसे सत्यापित किया जाना चाहिए तो शून्य से अधिक Text Signature ID निर्दिष्ट करें। |
| [setSignatureID(int value)](#setSignatureID-int-) | यदि इसे सत्यापित किया जाना चाहिए तो शून्य से अधिक Text Signature ID निर्दिष्ट करें। |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है।

### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


सत्यापन पाठ के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित किया जाने वाला पाठ |

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


सत्यापित करने के लिए Text गुण और हस्ताक्षर कार्यान्वयन के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| पाठ | java.lang.String | सत्यापित किया जाने वाला पाठ। |
| कार्यान्वयन | int | हस्ताक्षर कार्यान्वयन प्रकार। |

### getText() {#getText--}
```
public final String getText()
```


यदि इसे सत्यापित किया जाना चाहिए तो हस्ताक्षर पाठ निर्दिष्ट करें।

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


यदि इसे सत्यापित किया जाना चाहिए तो हस्ताक्षर पाठ निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Text Match Type सत्यापन को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Text Match Type सत्यापन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। यदि यह गुण सेट किया गया है तो पाठ केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


फ़ॉर्म फ़ील्ड का शीर्षक प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। यदि यह गुण सेट किया गया है तो पाठ केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। यदि यह गुण सेट किया गया है तो पाठ केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।

**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


फ़ॉर्म फ़ील्ड का प्रकार प्राप्त करता है या सेट करता है ताकि इसे सत्यापित किया जा सके। यदि यह गुण सेट किया गया है तो पाठ केवल टेक्स्ट फ़ॉर्म फ़ील्ड में पाया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


यदि इसे सत्यापित किया जाना चाहिए तो शून्य से अधिक Text Signature ID निर्दिष्ट करें। यह गुण केवल PDF दस्तावेज़ों के लिए समर्थित है।

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


यदि इसे सत्यापित किया जाना चाहिए तो शून्य से अधिक Text Signature ID निर्दिष्ट करें। यह गुण केवल PDF दस्तावेज़ों के लिए समर्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।

**Returns:**
java.lang.String -
