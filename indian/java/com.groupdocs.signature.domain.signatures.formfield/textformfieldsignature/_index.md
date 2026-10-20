---
title: "TextFormFieldSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Pdf दस्तावेज़ के लिए टेक्स्ट इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

Pdf दस्तावेज़ के लिए टेक्स्ट इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature बनाता है। |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getText()](#getText--) | फ़ॉर्म फ़ील्ड टेक्स्ट इनपुट का टेक्स्ट प्राप्त करता है या सेट करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | फ़ॉर्म फ़ील्ड टेक्स्ट इनपुट का टेक्स्ट प्राप्त करता है या सेट करता है। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | FormField Signature का प्रतिलिपि बनाता है। |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


पूर्वनिर्धारित नाम के साथ PdfTextFormFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|
|  | पाठ | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का टेक्स्ट। |
|

### getText() {#getText--}
```
public final String getText()
```


फ़ॉर्म फ़ील्ड टेक्स्ट इनपुट का टेक्स्ट प्राप्त करता है या सेट करता है।


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


फ़ॉर्म फ़ील्ड टेक्स्ट इनपुट का टेक्स्ट प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | हस्ताक्षर | java.lang.Object | तुलना के लिए हस्ताक्षर ऑब्जेक्ट। |
|

**Returns:**
boolean - true लौटाता है यदि पास किया गया हस्ताक्षर ऑब्जेक्ट समान प्रकार का है और उसकी सभी गुण इस इंस्टेंस के गुणों के बराबर हैं।

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है


**Returns:**
int - हस्ताक्षर हैश कोड

### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature का प्रतिलिपि बनाता है।


**Returns:**
java.lang.Object - क्लोन किए गए FormField Signature इंस्टेंस को लौटाता है।

