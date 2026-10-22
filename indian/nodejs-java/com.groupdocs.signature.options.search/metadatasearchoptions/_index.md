---
title: "MetadataSearchOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "मेटाडेटा हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।"
type: docs
weight: 15
url: /hi/nodejs-java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

मेटाडेटा हस्ताक्षरों के लिए सारभूत खोज विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MetadataSearchOptions()](#MetadataSearchOptions--) | डिफ़ॉल्ट मानों के साथ SearchMetadataOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | यदि मेटाडेटा सिग्नेचर नाम को खोजा और मिलाया जाना चाहिए तो उसे निर्दिष्ट करता है। |
| [setName(String value)](#setName-java.lang.String-) | यदि मेटाडेटा सिग्नेचर नाम को खोजा और मिलाया जाना चाहिए तो उसे निर्दिष्ट करता है। |
| [getNameMatchType()](#getNameMatchType--) | मेटाडेटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
| [setNameMatchType(int value)](#setNameMatchType-int-) | मेटाडेटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। |
| [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | यह दर्शाता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ सांख्यिकी, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। |
| [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | यह दर्शाता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ सांख्यिकी, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। |
| [getDataEncryption()](#getDataEncryption--) | QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है। |
| [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है। |
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


डिफ़ॉल्ट मानों के साथ SearchMetadataOptions क्लास की नई इंस्टेंस को इनिशियलाइज़ करता है।

### getName() {#getName--}
```
public final String getName()
```


यदि मेटाडेटा सिग्नेचर नाम को खोजा और मिलाया जाना चाहिए तो उसे निर्दिष्ट करता है।

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


यदि मेटाडेटा सिग्नेचर नाम को खोजा और मिलाया जाना चाहिए तो उसे निर्दिष्ट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


मेटाडेटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग होता है जब Name प्रॉपर्टी सेट हो।

**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


मेटाडेटा नाम मैच टाइप खोज को प्राप्त करता है या सेट करता है। यह केवल तब उपयोग होता है जब Name प्रॉपर्टी सेट हो।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


यह दर्शाता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ सांख्यिकी, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। यह फ़्लैग प्रेज़ेंटेशन, स्प्रेडशीट और वर्ड प्रोसेसिंग दस्तावेज़ फ़ाइल प्रकारों के लिए मायने रखता है।

**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


यह दर्शाता है कि क्या बिल्ट-इन दस्तावेज़ प्रॉपर्टीज़ जैसे दस्तावेज़ सांख्यिकी, जानकारी आदि को खोज परिणाम में शामिल किया जाना चाहिए। यह फ़्लैग प्रेज़ेंटेशन, स्प्रेडशीट और वर्ड प्रोसेसिंग दस्तावेज़ फ़ाइल प्रकारों के लिए मायने रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है।

**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code हस्ताक्षर टेक्स्ट या डेटा गुणों को एन्कोड और डिकोड करने के लिए [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) इंटरफ़ेस के कार्यान्वयन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

