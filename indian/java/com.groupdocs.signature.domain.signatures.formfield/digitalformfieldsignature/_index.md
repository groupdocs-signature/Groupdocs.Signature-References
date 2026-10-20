---
title: "DigitalFormFieldSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Pdf दस्तावेज़ों के लिए डिजिटल हस्ताक्षर इनपुट फ़ॉर्म फ़ील्ड गुण शामिल हैं।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.domain.signatures.formfield/digitalformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class DigitalFormFieldSignature extends FormFieldSignature
```

Pdf दस्तावेज़ों के लिए डिजिटल हस्ताक्षर इनपुट फ़ॉर्म फ़ील्ड गुण शामिल हैं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalFormFieldSignature(String name)](#DigitalFormFieldSignature-java.lang.String-) | पूर्वनिर्धारित नाम के साथ PdfDigitalFormFieldSignature बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getSigned()](#getSigned--) | पढ़ने-केवल गुण जो दर्शाता है कि Form-field Signature डिजिटल प्रमाणपत्र से हस्ताक्षरित था या नहीं। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | FormField Signature का प्रतिलिपि बनाता है। |
|
### DigitalFormFieldSignature(String name) {#DigitalFormFieldSignature-java.lang.String-}
```
public DigitalFormFieldSignature(String name)
```


पूर्वनिर्धारित नाम के साथ PdfDigitalFormFieldSignature बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | फ़ॉर्म फ़ील्ड ऑब्जेक्ट का नाम। |
|

### getSigned() {#getSigned--}
```
public final boolean getSigned()
```


पढ़ने-केवल गुण जो दर्शाता है कि Form-field Signature डिजिटल प्रमाणपत्र से हस्ताक्षरित था या नहीं।


**Returns:**
boolean
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

