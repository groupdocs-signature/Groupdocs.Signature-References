---
title: "SymmetricEncryption"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "एकल कुंजी और पासफ़्रेज़ सॉल्ट के साथ डेटा एन्क्रिप्शन के लिए मानक सममित एल्गोरिदम को लागू करता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

एकल कुंजी और पासफ़्रेज़ (सॉल्ट) के साथ डेटा एन्क्रिप्शन के लिए मानक सममित एल्गोरिदम को लागू करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | पैरामीटरों के साथ सममित एन्क्रिप्शन एल्गोरिदम बनाता है। |
| [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | डिफ़ॉल्ट पासफ़्रेज़ के साथ सममित एन्क्रिप्शन एल्गोरिदम बनाता है |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getAlgorithmType()](#getAlgorithmType--) | सममित एल्गोरिदम का प्रकार प्राप्त करता है या सेट करता है। |
| [setAlgorithmType(int value)](#setAlgorithmType-int-) | सममित एल्गोरिदम का प्रकार प्राप्त करता है या सेट करता है। |
| [getKey()](#getKey--) | एन्क्रिप्शन एल्गोरिदम की कुंजी प्राप्त करता है या सेट करता है। |
| [setKey(String value)](#setKey-java.lang.String-) | एन्क्रिप्शन एल्गोरिदम की कुंजी प्राप्त करता है या सेट करता है। |
| [getSalt()](#getSalt--) | एन्क्रिप्शन एल्गोरिदम का पासफ़्रेज़ प्राप्त करता है या सेट करता है। |
| [setSalt(String value)](#setSalt-java.lang.String-) | एन्क्रिप्शन एल्गोरिदम का पासफ़्रेज़ प्राप्त करता है या सेट करता है। |
| [encode(String source)](#encode-java.lang.String-) | प्रदान किए गए एल्गोरिदम प्रकार, कुंजी और सॉल्ट पैरामीटर के आधार पर स्ट्रिंग को एन्क्रिप्ट करता है |
| [decode(String source)](#decode-java.lang.String-) | प्रदान किए गए एल्गोरिदम प्रकार, कुंजी और सॉल्ट पैरामीटर के आधार पर स्ट्रिंग को डिक्रिप्ट करता है |
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


पैरामीटरों के साथ सममित एन्क्रिप्शन एल्गोरिदम बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| algorithmType | int | सममित एल्गोरिदम प्रकार निर्दिष्ट करें |
| कुंजी | java.lang.String | एन्क्रिप्शन कुंजी |
| सॉल्ट | java.lang.String | एन्क्रिप्शन के लिए पासफ़्रेज़ |

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


डिफ़ॉल्ट पासफ़्रेज़ के साथ सममित एन्क्रिप्शन एल्गोरिदम बनाता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| algorithmType | int | सममित एल्गोरिदम प्रकार निर्दिष्ट करें |
| कुंजी | java.lang.String | एन्क्रिप्शन कुंजी |

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


सममित एल्गोरिदम का प्रकार प्राप्त करता है या सेट करता है।

**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


सममित एल्गोरिदम का प्रकार प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


एन्क्रिप्शन एल्गोरिदम की कुंजी प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


एन्क्रिप्शन एल्गोरिदम की कुंजी प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


एन्क्रिप्शन एल्गोरिदम का पासफ़्रेज़ प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


एन्क्रिप्शन एल्गोरिदम का पासफ़्रेज़ प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


प्रदान किए गए एल्गोरिदम प्रकार, कुंजी और सॉल्ट पैरामीटर के आधार पर स्ट्रिंग को एन्क्रिप्ट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्रोत | java.lang.String | एन्कोड करने के लिए स्रोत स्ट्रिंग। |

**Returns:**
java.lang.String - एन्क्रिप्टेड स्ट्रिंग लौटाता है।
### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


प्रदान किए गए एल्गोरिदम प्रकार, कुंजी और सॉल्ट पैरामीटर के आधार पर स्ट्रिंग को डिक्रिप्ट करता है

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्रोत | java.lang.String | डिकोड करने के लिए एन्क्रिप्टेड स्ट्रिंग। |

**Returns:**
java.lang.String - डिक्रिप्टेड स्ट्रिंग लौटाता है।
