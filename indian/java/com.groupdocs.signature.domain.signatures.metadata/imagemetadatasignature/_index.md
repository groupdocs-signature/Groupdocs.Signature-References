---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "छवि मेटाडेटा हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

छवि मेटाडेटा हस्ताक्षर गुण शामिल हैं।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | आईडी और मान के साथ इमेज मेटाडाटा हस्ताक्षर बनाता है |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getId()](#getId--) | इमेज मेटाडाटा हस्ताक्षर का पहचानकर्ता। |
|
|  | [setId(int value)](#setId-int-) | इमेज मेटाडाटा हस्ताक्षर का पहचानकर्ता। |
|
|  | [getSize()](#getSize--) | केवल-पढ़ने योग्य मान जो मेटाडाटा मान का आकार प्राप्त करता है |
|
|  | [setSize(int value)](#setSize-int-) | केवल-पढ़ने योग्य मान जो मेटाडाटा मान का आकार प्राप्त करता है |
|
|  | [getDescription()](#getDescription--) | केवल-पढ़ने योग्य मान जो मानक इमेज मेटाडाटा हस्ताक्षर के विवरण को प्राप्त करता है |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [deepClone()](#deepClone--) | Metadata Signature की प्रति बनाएं। |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ इमेज मेटाडाटा हस्ताक्षर की प्रति बनाता है। |
|
|  | [toBoolean()](#toBoolean--) | बूलियन में परिवर्तित करता है। |
|
|  | [toInteger()](#toInteger--) | इंटीजर में परिवर्तित करता है। |
|
|  | [toLong()](#toLong--) | लॉन्ग में परिवर्तित करता है। |
|
|  | [toSingle()](#toSingle--) | फ़्लोट में परिवर्तित करता है। |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | फ़्लोट में परिवर्तित करता है। |
|
|  | [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | डबल में परिवर्तित करता है। |
|
|  | [toDecimal()](#toDecimal--) | डेसिमल में परिवर्तित करता है। |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | डेसिमल में परिवर्तित करता है। |
|
|  | [toDateTime()](#toDateTime--) | डेटटाइम में परिवर्तित करता है। |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | डेटटाइम में परिवर्तित करता है। |
|
|  | [toString()](#toString--) | ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है |
|
|  | [toString(String format)](#toString-java.lang.String-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है |
|
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


आईडी और मान के साथ इमेज मेटाडाटा हस्ताक्षर बनाता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | आईडी | int | छवि Image Metadata Signature नाम का अद्वितीय पहचानकर्ता। संभावित id मानों के लिए Exif टैग विनिर्देशों के संदर्भ देखें। |
|
|  | मान | java.lang.Object | Metadata मान |
|

### getId() {#getId--}
```
public final int getId()
```


इमेज मेटाडाटा हस्ताक्षर का पहचानकर्ता।
देखें [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) क्लास जिसमें पूर्वनिर्धारित आईडी मान के साथ मानक हस्ताक्षर शामिल है।


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


इमेज मेटाडाटा हस्ताक्षर का पहचानकर्ता।
देखें [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) क्लास जिसमें पूर्वनिर्धारित आईडी मान के साथ मानक हस्ताक्षर शामिल है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


केवल-पढ़ने योग्य मान जो मेटाडाटा मान का आकार प्राप्त करता है


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


केवल-पढ़ने योग्य मान जो मेटाडाटा मान का आकार प्राप्त करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


केवल-पढ़ने योग्य मान जो मानक इमेज मेटाडाटा हस्ताक्षर के विवरण को प्राप्त करता है


**Returns:**
java.lang.String
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


Metadata Signature की प्रति बनाएं।


**Returns:**
java.lang.Object - क्लोन किए गए Metadata Signature इंस्टेंस को लौटाता है

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


दिए गए मान के साथ इमेज मेटाडाटा हस्ताक्षर की प्रति बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


बूलियन में परिवर्तित करता है।


**Returns:**
boolean - मेटाडेटा सिग्नेचर मान को बूलियन के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


इंटीजर में परिवर्तित करता है।


**Returns:**
int - मेटाडेटा सिग्नेचर मान को इंटीजर के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


लॉन्ग में परिवर्तित करता है।


**Returns:**
long - मेटाडाटा हस्ताक्षर मान को लॉन्ग के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


फ़्लोट में परिवर्तित करता है।


**Returns:**
float - इमेज मेटाडाटा हस्ताक्षर मान को फ़्लोट के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture का उपयोग किया जाएगा।

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


फ़्लोट में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />

|

**Returns:**
float - मेटाडेटा सिग्नेचर मान को फ़्लोट के रूप में लौटाता है।

### toDouble() {#toDouble--}
```
public double toDouble()
```


डबल में परिवर्तित करता है।


**Returns:**
double - इमेज मेटाडाटा हस्ताक्षर मान को डबल के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture का उपयोग किया जाएगा।

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


डबल में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />

|

**Returns:**
double - मेटाडेटा सिग्नेचर मान को डबल के रूप में लौटाता है।

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


डेसिमल में परिवर्तित करता है।


**Returns:**
java.math.BigDecimal - इमेज मेटाडाटा हस्ताक्षर मान को डेसिमल के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture का उपयोग किया जाएगा।

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


डेसिमल में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />

|

**Returns:**
java.math.BigDecimal - मेटाडाटा हस्ताक्षर मान को डेसिमल के रूप में लौटाता है।

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


डेटटाइम में परिवर्तित करता है।


**Returns:**
java.util.Date - मेटाडेटा सिग्नेचर मान को DateTime के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture का उपयोग किया जाएगा।

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


डेटटाइम में परिवर्तित करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है।

<br />

|

**Returns:**
java.util.Date - मेटाडेटा सिग्नेचर मान को DateTime के रूप में लौटाता है।

### toString() {#toString--}
```
public String toString()
```


ओवरराइड ToString() मेथड के साथ स्ट्रिंग में परिवर्तित करता है


**Returns:**
java.lang.String - मेटाडेटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |

<br />

*** ** * ** ***

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है। डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture का उपयोग किया जाएगा।

<br />

|

**Returns:**
java.lang.String - मेटाडेटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


निर्दिष्ट फ़ॉर्मेट के साथ स्ट्रिंग में परिवर्तित करता है


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | फ़ॉर्मेट | java.lang.String | डेटा फ़ॉर्मेट स्ट्रिंग। |
|
|  | प्रोवाइडर | java.util.Locale | डेटा रूपांतरण ऑपरेशन्स के साथ उपयोग करने के लिए फ़ॉर्मेट डेटा प्रोवाइडर। |

<br />

*** ** * ** ***

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है।

<br />

|

**Returns:**
java.lang.String - मेटाडेटा सिग्नेचर मान को स्ट्रिंग के रूप में लौटाता है।

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

