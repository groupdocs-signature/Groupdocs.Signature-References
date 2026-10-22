---
title: "ImageMetadataSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "इमेज मेटाडेटा हस्ताक्षर प्रॉपर्टीज़ शामिल करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

इमेज मेटाडेटा हस्ताक्षर प्रॉपर्टीज़ शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Image Metadata Signature को Id और मान के साथ बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getId()](#getId--) | Image Metadata signature का पहचानकर्ता। |
| [setId(int value)](#setId-int-) | Image Metadata signature का पहचानकर्ता। |
| [getSize()](#getSize--) | Metadata मान के आकार को प्राप्त करने के लिए केवल-पढ़ने योग्य मान |
| [setSize(int value)](#setSize-int-) | Metadata मान के आकार को प्राप्त करने के लिए केवल-पढ़ने योग्य मान |
| [getDescription()](#getDescription--) | मानक Image Metadata signature के विवरण को प्राप्त करने के लिए केवल-पढ़ने योग्य मान |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | Metadata Signature इंस्टेंस को क्लोन करें। |
| [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ Image Metadata Signature इंस्टेंस को क्लोन करें। |
| [toBoolean()](#toBoolean--) | बूलियन में परिवर्तित करता है। |
| [toInteger()](#toInteger--) | इंटीजर में परिवर्तित करता है। |
| [toLong()](#toLong--) | long में परिवर्तित करता है। |
| [toSingle()](#toSingle--) | फ़्लोट में परिवर्तित करता है। |
| [toSingle(Locale provider)](#toSingle-java.util.Locale-) | फ़्लोट में परिवर्तित करता है। |
| [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
| [toDouble(Locale provider)](#toDouble-java.util.Locale-) | डबल में परिवर्तित करता है। |
| [toDecimal()](#toDecimal--) | Decimal में परिवर्तित करता है। |
| [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Decimal में परिवर्तित करता है। |
| [toDateTime()](#toDateTime--) | DateTime में परिवर्तित करता है। |
| [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | DateTime में परिवर्तित करता है। |
| [toString()](#toString--) | ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है। |
| [toString(String format)](#toString-java.lang.String-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है। |
| [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है। |
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Image Metadata Signature को Id और मान के साथ बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| आईडी | int | इमेज Metadata Signature नाम का अद्वितीय पहचानकर्ता। संभावित id मानों के लिए Exif टैग विनिर्देशों के संदर्भ देखें। |
| मान | java.lang.Object | मेटाडेटा मान |

### getId() {#getId--}
```
public final int getId()
```


Image Metadata signature का पहचानकर्ता। देखें [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) क्लास जिसमें पूर्वनिर्धारित Id मान के साथ मानक Signature शामिल है।

**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Image Metadata signature का पहचानकर्ता। देखें [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) क्लास जिसमें पूर्वनिर्धारित Id मान के साथ मानक Signature शामिल है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Metadata मान के आकार को प्राप्त करने के लिए केवल-पढ़ने योग्य मान

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Metadata मान के आकार को प्राप्त करने के लिए केवल-पढ़ने योग्य मान

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


मानक Image Metadata signature के विवरण को प्राप्त करने के लिए केवल-पढ़ने योग्य मान

**Returns:**
java.lang.String
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


Metadata Signature इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किए गए Metadata Signature इंस्टेंस को लौटाता है
### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


दिए गए मान के साथ Image Metadata Signature इंस्टेंस को क्लोन करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.
### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


बूलियन में परिवर्तित करता है।

**Returns:**
boolean - मेटाडाटा सिग्नेचर मान को बूलियन के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है।
### toInteger() {#toInteger--}
```
public int toInteger()
```


इंटीजर में परिवर्तित करता है।

**Returns:**
int - मेटाडाटा सिग्नेचर मान को पूर्णांक के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है।
### toLong() {#toLong--}
```
public final long toLong()
```


long में परिवर्तित करता है।

**Returns:**
long - Metadata Signature मान को long के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है।
### toSingle() {#toSingle--}
```
public final float toSingle()
```


फ़्लोट में परिवर्तित करता है।

**Returns:**
float - Image Metadata Signature मान को float के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से उपयोग की जाएगी  SignatureSettings.DefaultCulture
### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


फ़्लोट में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है |

**Returns:**
float - मेटाडाटा सिग्नेचर मान को फ़्लोट के रूप में लौटाता है।
### toDouble() {#toDouble--}
```
public double toDouble()
```


डबल में परिवर्तित करता है।

**Returns:**
double - Image Metadata Signature मान को Double के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से उपयोग की जाएगी  SignatureSettings.DefaultCulture
### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


डबल में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है |

**Returns:**
double - मेटाडाटा सिग्नेचर मान को डबल के रूप में लौटाता है।
### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Decimal में परिवर्तित करता है।

**Returns:**
java.math.BigDecimal - Image Metadata Signature मान को Decimal के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से उपयोग की जाएगी  SignatureSettings.DefaultCulture
### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Decimal में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है |

**Returns:**
java.math.BigDecimal - Metadata Signature मान को Decimal के रूप में लौटाता है।
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


DateTime में परिवर्तित करता है।

**Returns:**
java.util.Date - मेटाडाटा सिग्नेचर मान को DateTime के रूप में लौटाता है।

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से उपयोग की जाएगी  SignatureSettings.DefaultCulture
### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


DateTime में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

यदि मेटाडाटा मान को परिवर्तित नहीं किया जा सका तो एक अपवाद फेंकता है |

**Returns:**
java.util.Date - मेटाडाटा सिग्नेचर मान को DateTime के रूप में लौटाता है।
### toString() {#toString--}
```
public String toString()
```


ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है।

**Returns:**
java.lang.String - मेटाडाटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।
### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
|  | फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |

--------------------

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से उपयोग की जाएगी  SignatureSettings.DefaultCulture  |

**Returns:**
java.lang.String - मेटाडाटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।
### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण संचालन के साथ उपयोग करने के लिए डेटा प्रोवाइडर को फ़ॉर्मेट करें। |

--------------------

एक बूलियन प्रॉपर्टी को \"True\" या \"False\" में परिवर्तित करता है। |

**Returns:**
java.lang.String - मेटाडाटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।
### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

