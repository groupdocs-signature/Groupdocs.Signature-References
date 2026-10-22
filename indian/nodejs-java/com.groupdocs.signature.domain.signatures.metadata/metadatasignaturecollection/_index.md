---
title: "MetadataSignatureCollection"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Metadata हस्ताक्षर वस्तुओं का संग्रह।"
type: docs
weight: 13
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

Metadata हस्ताक्षर वस्तुओं का संग्रह।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Metadata हस्ताक्षर का संग्रह बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCount()](#getCount--) | संग्रह में वस्तुओं की संख्या प्राप्त करता है। |
| [clear()](#clear--) | संग्रह से सभी वस्तुओं को हटाता है। |
| [contains(String name)](#contains-java.lang.String-) | यदि निर्दिष्ट नाम वाला Metadata संग्रह में मौजूद है तो true लौटाता है। |
| [indexOf(String name)](#indexOf-java.lang.String-) | नाम द्वारा प्रॉपर्टी का इंडेक्स प्राप्त करता है। |
| [remove(String name)](#remove-java.lang.String-) | निर्दिष्ट नाम वाले Metadata Signature को संग्रह से हटाता है। |
| [removeAt(int index)](#removeAt-int-) | निर्दिष्ट इंडेक्स पर Metadata Signature को हटाता है। |
| [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | संग्रह में Metadata Signature ऑब्जेक्ट जोड़ें। |
| [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | Metadata Signature संग्रह जोड़ें। |
| [deepClone()](#deepClone--) | Metadata Signature आइटम्स के साथ Metadata Signature Collection क्लास को क्लोन करें। |
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Metadata हस्ताक्षर का संग्रह बनाता है।

### getCount() {#getCount--}
```
public final int getCount()
```


संग्रह में वस्तुओं की संख्या प्राप्त करता है।

**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


संग्रह से सभी वस्तुओं को हटाता है।

### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


यदि निर्दिष्ट नाम वाला Metadata संग्रह में मौजूद है तो true लौटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | प्रॉपर्टी का केस-इंसेंसिटिव नाम। |

**Returns:**
boolean - यदि Metadata संग्रह में मौजूद है तो True; अन्यथा false।
### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


नाम द्वारा प्रॉपर्टी का इंडेक्स प्राप्त करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | MetadataSignature का केस-इंसेंसिटिव नाम। |

**Returns:**
int - शून्य-आधारित इंडेक्स। यदि नहीं मिला तो नकारात्मक मान।
### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


निर्दिष्ट नाम वाले Metadata Signature को संग्रह से हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| नाम | java.lang.String | Metadata Signature का केस-इंसेंसिटिव नाम। |

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


निर्दिष्ट इंडेक्स पर Metadata Signature को हटाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| इंडेक्स | int | शून्य-आधारित इंडेक्स। |

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


संग्रह में Metadata Signature ऑब्जेक्ट जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | संग्रह में जोड़ने के लिए Metadata signature। |

--------------------

यदि नाम मान पूरी मौजूदा संग्रह में अद्वितीय नहीं है तो अपवाद फेंकता है |

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


Metadata Signature संग्रह जोड़ें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | जोड़ने के लिए हस्ताक्षरों का संग्रह। |

--------------------

यदि नाम मान पूरी मौजूदा संग्रह में अद्वितीय नहीं है तो अपवाद फेंकता है |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


Metadata Signature आइटम्स के साथ Metadata Signature Collection क्लास को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किए गए Signature आइटम्स के साथ कॉपी किया गया इंस्टेंस लौटाता है
