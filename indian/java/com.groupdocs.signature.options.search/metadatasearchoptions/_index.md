---
title: "MetadataSearchOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "Metadata हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

Metadata हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।

## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | डिफ़ॉल्ट मानों के साथ SearchMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getName()](#getName--) | यदि इसे खोजा और मिलाया जाना चाहिए तो मेटाडाटा सिग्नेचर नाम निर्दिष्ट करता है। |
|
|  | [setName(String value)](#setName-java.lang.String-) | यदि इसे खोजा और मिलाया जाना चाहिए तो मेटाडाटा सिग्नेचर नाम निर्दिष्ट करता है। |
|
|  | [getNameMatchType()](#getNameMatchType--) | मेटाडाटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | मेटाडाटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | निर्देशित करता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ आँकड़े, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | निर्देशित करता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ आँकड़े, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। |
|
|  | [getDataEncryption()](#getDataEncryption--) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है। |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


डिफ़ॉल्ट मानों के साथ SearchMetadataOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।


### getName() {#getName--}
```
public final String getName()
```


यदि इसे खोजा और मिलाया जाना चाहिए तो मेटाडाटा सिग्नेचर नाम निर्दिष्ट करता है।


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


यदि इसे खोजा और मिलाया जाना चाहिए तो मेटाडाटा सिग्नेचर नाम निर्दिष्ट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


मेटाडाटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग किया जाता है जब Name प्रॉपर्टी सेट हो।


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


मेटाडाटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग किया जाता है जब Name प्रॉपर्टी सेट हो।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


निर्देशित करता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ आँकड़े, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए।
यह फ़्लैग प्रेज़ेंटेशन, स्प्रेडशीट और वर्ड प्रोसेसिंग दस्तावेज़ फ़ाइल प्रकारों के लिए उपयोगी है।


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


निर्देशित करता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ आँकड़े, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए।
यह फ़्लैग प्रेज़ेंटेशन, स्प्रेडशीट और वर्ड प्रोसेसिंग दस्तावेज़ फ़ाइल प्रकारों के लिए उपयोगी है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को QR-Code हस्ताक्षर टेक्स्ट या डेटा प्रॉपर्टीज़ को एन्कोड और डिकोड करने के लिए प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

