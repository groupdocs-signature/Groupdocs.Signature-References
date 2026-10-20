---
title: "TextSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Text सिग्नेचर गुणों को शामिल करता है।"
type: docs
weight: 18
url: /hi/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

Text सिग्नेचर गुणों को शामिल करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ TextSignature ऑब्जेक्ट को प्रारंभ करें। |
|
| [TextSignature()](#TextSignature--) |  |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getText()](#getText--) | हस्ताक्षर में पाठ निर्दिष्ट करता है। |
|
|  | [setText(String value)](#setText-java.lang.String-) | हस्ताक्षर में पाठ निर्दिष्ट करता है। |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | पाठ हस्ताक्षर कार्यान्वयन निर्दिष्ट करता है। |
|
|  | [getNative()](#getNative--) | मूल गुण निर्दिष्ट करता है। |
|
|  | [setNative(boolean value)](#setNative-boolean-) | मूल गुण निर्दिष्ट करता है। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | Text Signature इंस्टेंस को क्लोन करें। |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


खोज प्रक्रिया के बाद प्राप्त हस्ताक्षर पहचानकर्ता के साथ TextSignature ऑब्जेक्ट को प्रारंभ करें।
इस अद्वितीय पहचानकर्ता का उपयोग दस्तावेज़ हस्ताक्षर सूचना परत से इस हस्ताक्षर के अतिरिक्त गुण खोजने के लिए किया जाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | signatureId | java.lang.String | साइन या खोज विधि द्वारा प्राप्त अद्वितीय हस्ताक्षर पहचानकर्ता। |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


हस्ताक्षर में पाठ निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


हस्ताक्षर में पाठ निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


पाठ हस्ताक्षर कार्यान्वयन निर्दिष्ट करता है।


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


मूल गुण निर्दिष्ट करता है। यदि हस्ताक्षर दस्तावेज़-विशिष्ट है तो यह सत्य होता है।


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


मूल गुण निर्दिष्ट करता है। यदि हस्ताक्षर दस्तावेज़-विशिष्ट है तो यह सत्य होता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

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


Text Signature इंस्टेंस को क्लोन करें।


**Returns:**
java.lang.Object - क्लोन किया गया टेक्स्ट हस्ताक्षर इंस्टेंस लौटाता है।

