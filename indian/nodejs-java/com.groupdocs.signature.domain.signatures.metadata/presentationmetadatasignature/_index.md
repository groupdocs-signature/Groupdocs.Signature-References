---
title: "PresentationMetadataSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Presentation Metadata हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 16
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/presentationmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PresentationMetadataSignature extends MetadataSignature
```

Presentation Metadata हस्ताक्षर गुण शामिल हैं।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PresentationMetadataSignature(String name)](#PresentationMetadataSignature-java.lang.String-) | पूर्वनिर्धारित नाम और खाली मान के साथ प्रेज़ेंटेशन मेटाडाटा सिग्नेचर बनाता है |
| [PresentationMetadataSignature(String name, Object value)](#PresentationMetadataSignature-java.lang.String-java.lang.Object-) | पूर्वनिर्धारित मानों के साथ प्रेज़ेंटेशन मेटाडाटा सिग्नेचर बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [deepClone()](#deepClone--) | Metadata Signature इंस्टेंस को क्लोन करें। |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ स्लाइड्स मेटाडाटा सिग्नेचर इंस्टेंस को क्लोन करता है। |
| [toString()](#toString--) | ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है। |
| [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है। |
### PresentationMetadataSignature(String name) {#PresentationMetadataSignature-java.lang.String-}
```
public PresentationMetadataSignature(String name)
```


पूर्वनिर्धारित नाम और खाली मान के साथ प्रेज़ेंटेशन मेटाडाटा सिग्नेचर बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Presentation Metadata Signature नाम |

### PresentationMetadataSignature(String name, Object value) {#PresentationMetadataSignature-java.lang.String-java.lang.Object-}
```
public PresentationMetadataSignature(String name, Object value)
```


पूर्वनिर्धारित मानों के साथ प्रेज़ेंटेशन मेटाडाटा सिग्नेचर बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Metadata हस्ताक्षर ऑब्जेक्ट का नाम |
| मान | java.lang.Object | Metadata हस्ताक्षर का मान |

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


दिए गए मान के साथ स्लाइड्स मेटाडाटा सिग्नेचर इंस्टेंस को क्लोन करता है।

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
