---
title: "FormFieldSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | फ़ॉर्म फ़ील्ड का अद्वितीय नाम निर्दिष्ट करता है। |
| [setName(String value)](#setName-java.lang.String-) | फ़ॉर्म फ़ील्ड का अद्वितीय नाम निर्दिष्ट करता है। |
| [getType()](#getType--) | फ़ॉर्म फ़ील्ड प्रकार निर्दिष्ट करता है। |
| [getValue()](#getValue--) | फ़ॉर्म फ़ील्ड डेटा ऑब्जेक्ट निर्दिष्ट करता है। |
| [setValue(Object value)](#setValue-java.lang.Object-) | फ़ॉर्म फ़ील्ड डेटा ऑब्जेक्ट निर्दिष्ट करता है। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | FormField Signature इंस्टेंस को क्लोन करता है। |
### getName() {#getName--}
```
public final String getName()
```


फ़ॉर्म फ़ील्ड का अद्वितीय नाम निर्दिष्ट करता है।

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


फ़ॉर्म फ़ील्ड का अद्वितीय नाम निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


फ़ॉर्म फ़ील्ड प्रकार निर्दिष्ट करता है।

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


फ़ॉर्म फ़ील्ड डेटा ऑब्जेक्ट निर्दिष्ट करता है।

**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


फ़ॉर्म फ़ील्ड डेटा ऑब्जेक्ट निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

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
