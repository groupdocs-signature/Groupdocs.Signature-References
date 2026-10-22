---
title: "CheckboxFormFieldSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "चेक-बॉक्स इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/checkboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class CheckboxFormFieldSignature extends FormFieldSignature
```

चेक-बॉक्स इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CheckboxFormFieldSignature(String name)](#CheckboxFormFieldSignature-java.lang.String-) | पूर्वनिर्धारित नाम के साथ PdfCheckboxFormFieldSignature बनाता है। |
| [CheckboxFormFieldSignature(String name, boolean isChecked)](#CheckboxFormFieldSignature-java.lang.String-boolean-) | पूर्वनिर्धारित नाम और मान के साथ PdfCheckboxFormFieldSignature बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getChecked()](#getChecked--) | फ़ॉर्म फ़ील्ड चेक-बॉक्स इनपुट का चयनित मान प्राप्त करता है या सेट करता है। |
| [setChecked(boolean value)](#setChecked-boolean-) | फ़ॉर्म फ़ील्ड चेक-बॉक्स इनपुट का चयनित मान प्राप्त करता है या सेट करता है। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | FormField Signature इंस्टेंस को क्लोन करता है। |
### CheckboxFormFieldSignature(String name) {#CheckboxFormFieldSignature-java.lang.String-}
```
public CheckboxFormFieldSignature(String name)
```


पूर्वनिर्धारित नाम के साथ PdfCheckboxFormFieldSignature बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |

### CheckboxFormFieldSignature(String name, boolean isChecked) {#CheckboxFormFieldSignature-java.lang.String-boolean-}
```
public CheckboxFormFieldSignature(String name, boolean isChecked)
```


पूर्वनिर्धारित नाम और मान के साथ PdfCheckboxFormFieldSignature बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
| isChecked | boolean | यदि चेक बॉक्स चयनित हो तो मान। |

### getChecked() {#getChecked--}
```
public final boolean getChecked()
```


फ़ॉर्म फ़ील्ड चेक-बॉक्स इनपुट का चयनित मान प्राप्त करता है या सेट करता है।

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public final void setChecked(boolean value)
```


फ़ॉर्म फ़ील्ड चेक-बॉक्स इनपुट का चयनित मान प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| हस्ताक्षर | java.lang.Object | तुलना के लिए हस्ताक्षर ऑब्जेक्ट। |

**Returns:**
boolean - यदि पास किया गया हस्ताक्षर ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस की गुणों के बराबर हैं तो true लौटाता है।
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है।

**Returns:**
int - हस्ताक्षर हैश कोड
### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature इंस्टेंस को क्लोन करता है।

**Returns:**
java.lang.Object - क्लोन किए गए FormField Signature इंस्टेंस को लौटाता है।
