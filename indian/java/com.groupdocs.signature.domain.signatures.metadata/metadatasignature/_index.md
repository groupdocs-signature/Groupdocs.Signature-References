---
title: "MetadataSignature"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "मेटाडेटा हस्ताक्षर गुण शामिल हैं।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

मेटाडेटा हस्ताक्षर गुण शामिल हैं।

## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | विशिष्ट मेटाडेटा नाम निर्दिष्ट करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | विशिष्ट मेटाडेटा नाम निर्दिष्ट करता है। |
|
|  | [getValue()](#getValue--) | मेटाडेटा ऑब्जेक्ट निर्दिष्ट करता है। |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | मेटाडेटा ऑब्जेक्ट निर्दिष्ट करता है। |
|
|  | [getType()](#getType--) | मेटाडेटा वैल्यू प्रकार निर्दिष्ट करता है। |
|
|  | [setType(int value)](#setType-int-) | मेटाडेटा वैल्यू प्रकार निर्दिष्ट करता है। |
|
|  | [getDataEncryption()](#getDataEncryption--) | हस्ताक्षर वैल्यू प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है। |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | हस्ताक्षर वैल्यू प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है। |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | डिसेरियलाइज़ेशन के बाद मेटाडेटा सिग्नेचर वैल्यू से ऑब्जेक्ट प्राप्त करें। |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | डिसेरियलाइज़ेशन के बाद मेटाडेटा सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें। |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
|
|  | [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है |
|
|  | [toBoolean()](#toBoolean--) | बूलियन में परिवर्तित करता है। |
|
|  | [toInteger()](#toInteger--) | इंटीजर में परिवर्तित करता है। |
|
|  | [toDouble()](#toDouble--) | डबल में परिवर्तित करता है। |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | डबल में परिवर्तित करता है। |
|
|  | [toSingle()](#toSingle--) | फ़्लोट में परिवर्तित करता है। |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | फ़्लोट में परिवर्तित करता है। |
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
|  | [deepClone()](#deepClone--) | Metadata Signature की प्रति बनाएं। |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | दिए गए मान के साथ मेटाडेटा सिग्नेचर इंस्टेंस को क्लोन करता है। |
|
### getName() {#getName--}
```
public final String getName()
```


विशिष्ट मेटाडेटा नाम निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


विशिष्ट मेटाडेटा नाम निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


मेटाडेटा ऑब्जेक्ट निर्दिष्ट करता है।


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


मेटाडेटा ऑब्जेक्ट निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


मेटाडेटा वैल्यू प्रकार निर्दिष्ट करता है।


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


मेटाडेटा वैल्यू प्रकार निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


हस्ताक्षर वैल्यू प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है।


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


हस्ताक्षर वैल्यू प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस की कार्यान्वयन को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


डिसेरियलाइज़ेशन के बाद मेटाडेटा सिग्नेचर वैल्यू से ऑब्जेक्ट प्राप्त करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - T ऑब्जेक्ट का इंस्टेंस


T
: मेटाडेटा मान से डीसिरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


डिसेरियलाइज़ेशन के बाद मेटाडेटा सिग्नेचर टेक्स्ट से ऑब्जेक्ट प्राप्त करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | कस्टम डेटा एन्क्रिप्शन इम्प्लीमेंटेशन सेट करें |


T
: मेटाडेटा वैल्यू से डीसिरियलाइज़ करने के लिए ऑब्जेक्ट का प्रकार
|

**Returns:**
T -
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


### toDouble() {#toDouble--}
```
public double toDouble()
```


डबल में परिवर्तित करता है।


**Returns:**
double - मेटाडेटा सिग्नेचर मान को डबल के रूप में लौटाता है।

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


फ़्लोट में परिवर्तित करता है।


**Returns:**
float - मेटाडेटा सिग्नेचर मान को फ़्लोट के रूप में लौटाता है।

<br />

*** ** * ** ***

यदि मेटाडेटा मान को परिवर्तित नहीं किया जा सका तो एक एक्सेप्शन फेंकता है। यदि मूल मान स्ट्रिंग आधारित है तो डिफ़ॉल्ट कल्चर प्रॉपर्टी जानकारी SignatureSettings प्रॉपर्टीज़ से SignatureSettings.DefaultCulture () का उपयोग किया जाएगा।

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

एक बूलियन प्रॉपर्टी को "True" या "False" में परिवर्तित करता है। अन्य डेटा टाइप के लिए डिफ़ॉल्ट डेटा फ़ॉर्मेट प्रोवाइडर का उपयोग किया जाएगा।

<br />


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


दिए गए मान के साथ मेटाडेटा सिग्नेचर इंस्टेंस को क्लोन करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | मान | java.lang.Object | नए क्लोन किए गए ऑब्जेक्ट के लिए मान। |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

