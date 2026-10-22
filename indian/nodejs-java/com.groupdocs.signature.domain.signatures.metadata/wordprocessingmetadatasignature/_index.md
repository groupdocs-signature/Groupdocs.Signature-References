---
title: "WordProcessingMetadataSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "WordProcessing Metadata हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 18
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/wordprocessingmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class WordProcessingMetadataSignature extends MetadataSignature
```

WordProcessing Metadata हस्ताक्षर गुण शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WordProcessingMetadataSignature(String name)](#WordProcessingMetadataSignature-java.lang.String-) | पूर्वनिर्धारित नाम और खाली मान के साथ वर्डप्रोसेसिंग मेटाडेटा सिग्नेचर बनाता है। |
| [WordProcessingMetadataSignature(String name, Object value)](#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-) | पूर्वनिर्धारित मानों के साथ वर्डप्रोसेसिंग मेटाडेटा सिग्नेचर बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | Metadata Signature इंस्टेंस को क्लोन करें। |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ वर्ड्स मेटाडेटा सिग्नेचर इंस्टेंस को क्लोन करता है। |
| [toString()](#toString--) | ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है। |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है। |
### WordProcessingMetadataSignature(String name) {#WordProcessingMetadataSignature-java.lang.String-}
```
public WordProcessingMetadataSignature(String name)
```


पूर्वनिर्धारित नाम और खाली मान के साथ वर्डप्रोसेसिंग मेटाडेटा सिग्नेचर बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | वर्डप्रोसेसिंग मेटाडेटा सिग्नेचर का नाम। |

### WordProcessingMetadataSignature(String name, Object value) {#WordProcessingMetadataSignature-java.lang.String-java.lang.Object-}
```
public WordProcessingMetadataSignature(String name, Object value)
```


पूर्वनिर्धारित मानों के साथ वर्डप्रोसेसिंग मेटाडेटा सिग्नेचर बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Metadata signature ऑब्जेक्ट का नाम। |
| मान | java.lang.Object | Metadata signature का मान। |

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata Signature इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किए गए Metadata Signature इंस्टेंस को लौटाता है
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


दिए गए मान के साथ वर्ड्स मेटाडेटा सिग्नेचर इंस्टेंस को क्लोन करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toString() {#toString--}
```
public String toString()
```


ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - मेटाडाटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

--------------------

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। अन्य डेटा प्रकार के लिए डिफ़ॉल्ट डेटा फ़ॉर्मेट प्रोवाइडर उपयोग किया जाएगा।
### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |
|  | प्रोवाइडर | com.aspose.ms.System.IFormatProvider | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। |

**Returns:**
java.lang.String - मेटाडाटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।
