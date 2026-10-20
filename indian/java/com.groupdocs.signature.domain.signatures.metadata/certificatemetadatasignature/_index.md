---
title: "CertificateMetadataSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Certificate मेटाडेटा हस्ताक्षर गुणों को शामिल करता है।"
type: docs
weight: 10
url: /hi/java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

Certificate मेटाडेटा हस्ताक्षर गुणों को शामिल करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | पूर्वनिर्धारित नाम और खाली मान के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर बनाता है। |
|
|  | [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | पूर्वनिर्धारित मानों के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [deepClone()](#deepClone--) | Metadata Signature की प्रति बनाएं। |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर की प्रति बनाता है। |
|
|  | [toString()](#toString--) | ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है |
|
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


पूर्वनिर्धारित नाम और खाली मान के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | प्रमाणपत्र मेटाडाटा हस्ताक्षर नाम। |
|

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


पूर्वनिर्धारित मानों के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | नाम | java.lang.String | मेटाडाटा हस्ताक्षर ऑब्जेक्ट का नाम। |
|
|  | मान | java.lang.Object | Metadata हस्ताक्षर का मान। |
|

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata Signature की प्रति बनाएं।


**Returns:**
java.lang.Object - क्लोन किए गए Metadata Signature इंस्टेंस को लौटाता है

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


दिए गए मान के साथ प्रमाणपत्र मेटाडाटा हस्ताक्षर की प्रति बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है


**Returns:**
java.lang.String - मेटाडेटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

<br />

*** ** * ** ***

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है। अन्य डेटा टाइप के लिए डिफ़ॉल्ट डेटा फ़ॉर्मेट प्रोवाइडर का उपयोग किया जाएगा।

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |
|
|  | प्रोवाइडर | com.aspose.ms.System.IFormatProvider | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है।

<br />

|

**Returns:**
java.lang.String - मेटाडेटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

