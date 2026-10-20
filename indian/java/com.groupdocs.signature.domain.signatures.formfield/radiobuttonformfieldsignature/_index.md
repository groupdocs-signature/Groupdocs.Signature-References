---
title: "RadioButtonFormFieldSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "रेडियो-बटन इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 14
url: /hi/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

रेडियो-बटन इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | पूर्वनिर्धारित नाम के साथ RadioButtonFieldSignature बनाता है। |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | पूर्वनिर्धारित नाम और आइटम सूची के साथ RadioButtonFieldSignature बनाता है। |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | पूर्वनिर्धारित नाम, आइटम सूची और चयनित मान के साथ RadioButtonFieldSignature बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSelected()](#getSelected--) | चयनित मान शामिल है। |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | चयनित मान शामिल है। |
|
|  | [getItems()](#getItems--) | Radio buttons विकल्प सूची प्राप्त करें या सेट करें। |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | Radio buttons विकल्प सूची प्राप्त करें या सेट करें। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | FormField Signature का प्रतिलिपि बनाता है। |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


पूर्वनिर्धारित नाम के साथ RadioButtonFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


पूर्वनिर्धारित नाम और आइटम सूची के साथ RadioButtonFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|
|  | items | java.util.List<java.lang.String> | radio-button सूची के मान। |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


पूर्वनिर्धारित नाम, आइटम सूची और चयनित मान के साथ RadioButtonFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|
|  | items | java.util.List<java.lang.String> | radio-button सूची के मान। |
|
|  | selected | java.lang.Object | चयनित मान। |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


चयनित मान शामिल है।


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


चयनित मान शामिल है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


Radio buttons विकल्प सूची प्राप्त करें या सेट करें।


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


Radio buttons विकल्प सूची प्राप्त करें या सेट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.List<java.lang.String> |  |

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

