---
title: "ComboboxFormFieldSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "कॉम्बो-बॉक्स इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.formfield/comboboxformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class ComboboxFormFieldSignature extends FormFieldSignature
```

कॉम्बो-बॉक्स इनपुट फ़ॉर्म फ़ील्ड हस्ताक्षर गुण शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ComboboxFormFieldSignature(String name)](#ComboboxFormFieldSignature-java.lang.String-) | पूर्वनिर्धारित नाम के साथ ComboboxFormFieldSignature बनाता है। |
| [ComboboxFormFieldSignature(String name, List<String> items)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | पूर्वनिर्धारित नाम और विकल्प सूची के साथ ComboboxFormFieldSignature बनाता है। |
| [ComboboxFormFieldSignature(String name, List<String> items, Object selected)](#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | पूर्वनिर्धारित नाम, विकल्प सूची और चयनित मान के साथ ComboboxFormFieldSignature बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSelected()](#getSelected--) | चयनित मान प्राप्त करें या सेट करें। |
| [setSelected(String value)](#setSelected-java.lang.String-) | चयनित मान प्राप्त करें या सेट करें। |
| [getItems()](#getItems--) | कॉम्बो-बॉक्स विकल्प सूची प्राप्त करें या सेट करें। |
| [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | कॉम्बो-बॉक्स विकल्प सूची प्राप्त करें या सेट करें। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | FormField Signature इंस्टेंस को क्लोन करता है। |
### ComboboxFormFieldSignature(String name) {#ComboboxFormFieldSignature-java.lang.String-}
```
public ComboboxFormFieldSignature(String name)
```


पूर्वनिर्धारित नाम के साथ ComboboxFormFieldSignature बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |

### ComboboxFormFieldSignature(String name, List<String> items) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public ComboboxFormFieldSignature(String name, List<String> items)
```


पूर्वनिर्धारित नाम और विकल्प सूची के साथ ComboboxFormFieldSignature बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
| items | java.util.List<java.lang.String> | कॉम्बो-बॉक्स सूची के मान। |

### ComboboxFormFieldSignature(String name, List<String> items, Object selected) {#ComboboxFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public ComboboxFormFieldSignature(String name, List<String> items, Object selected)
```


पूर्वनिर्धारित नाम, विकल्प सूची और चयनित मान के साथ ComboboxFormFieldSignature बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
| items | java.util.List<java.lang.String> | कॉम्बो-बॉक्स सूची के मान। |
| selected | java.lang.Object | चयनित मान। |

### getSelected() {#getSelected--}
```
public final String getSelected()
```


चयनित मान प्राप्त करें या सेट करें।

**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


चयनित मान प्राप्त करें या सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


कॉम्बो-बॉक्स विकल्प सूची प्राप्त करें या सेट करें।

**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


कॉम्बो-बॉक्स विकल्प सूची प्राप्त करें या सेट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.List<java.lang.String> |  |

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
