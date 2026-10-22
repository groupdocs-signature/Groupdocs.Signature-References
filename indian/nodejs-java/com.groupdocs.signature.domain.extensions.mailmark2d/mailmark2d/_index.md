---
title: "Mailmark2D"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Royal Mail 2D Mailmark में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास"
type: docs
weight: 10
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Royal Mail 2D Mailmark में एम्बेडेड टेक्स्ट को एन्कोड और डिकोड करने के लिए क्लास
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [Mailmark2D()](#Mailmark2D--) | डिफ़ॉल्ट प्राथमिक और द्वितीयक डेटा मानों के साथ Royal Mail Mailmark संयुक्त डेटा बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getUPUCountryID()](#getUPUCountryID--) | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर। |
| [getInformationTypeID()](#getInformationTypeID--) | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है। |
| [getVersionID()](#getVersionID--) | प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है। |
| [getClass_()](#getClass---) | आइटम की वर्ग की पहचान करता है। |
| [setClass(String value)](#setClass-java.lang.String-) | आइटम की वर्ग की पहचान करता है। |
| [getSupplyChainID()](#getSupplyChainID--) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। |
| [setSupplyChainID(int value)](#setSupplyChainID-int-) | मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। |
| [getItemID()](#getItemID--) | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। |
| [setItemID(int value)](#setItemID-int-) | Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। |
| [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। |
| [getRTSFlag()](#getRTSFlag--) | वह फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | वह फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। |
| [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं। |
| [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं। |
| [getCustomerContent()](#getCustomerContent--) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान। |
| [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | DataMatrix बारकोड का एन्कोड मोड। |
| [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | DataMatrix बारकोड का एन्कोड मोड। |
| [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark Type Data Matrix बारकोड का आकार निर्धारित करता है। |
| [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark Type Data Matrix बारकोड का आकार निर्धारित करता है। |
| [deepClone()](#deepClone--) | इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है। |
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


डिफ़ॉल्ट प्राथमिक और द्वितीयक डेटा मानों के साथ Royal Mail Mailmark संयुक्त डेटा बनाता है।

### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


UPU Country ID की पहचान करता है। अधिकतम लंबाई: 4 अक्षर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है।

--------------------

वैध मान: "0" - घरेलू सॉर्टेड और अनसॉर्टेड "A" - ऑनलाइन पोस्टेज "B" - फ्रैंकिंग "C" - समेकन

**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


प्रत्येक उत्पाद प्रकार के लिए Royal Mail Mailmark बारकोड पेलोड की पहचान करता है।

--------------------

वैध मान: "0" - घरेलू सॉर्टेड और अनसॉर्टेड "A" - ऑनलाइन पोस्टेज "B" - फ्रैंकिंग "C" - समेकन

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


प्रत्येक Information Type ID के अनुसार बारकोड संस्करण की पहचान करता है।

--------------------

वैध मान: "1" - वर्तमान में केवल यह मान उपयोग किया जाता है (डिफ़ॉल्ट) "0" और "2" से "9" तथा "A" से "Z" संभावित भविष्य उपयोग के लिए आरक्षित हैं।

**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


आइटम की वर्ग की पहचान करता है।

--------------------

वैध मान: "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - इकॉनमी (रिटेल) "5" - डिफर्ड (रिटेल) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


आइटम की वर्ग की पहचान करता है।

--------------------

वैध मान: "1" - 1C (रिटेल) "2" - 2C (रिटेल) "3" - इकॉनमी (रिटेल) "5" - डिफर्ड (रिटेल) "8" - प्रीमियम (नेटवर्क एक्सेस) "9" - स्टैंडर्ड (नेटवर्क एक्सेस)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


मेलिंग में शामिल ग्राहकों के अद्वितीय समूह की पहचान करता है। अधिकतम मान: 9999999।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को कम से कम 90 दिनों के लिए अद्वितीय रूप से पहचाने जाने हेतु एक ID लेनी आवश्यक है। अधिकतम मान: 99999999।

**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Supply Chain ID के भीतर अद्वितीय आइटम की पहचान करता है। प्रत्येक Mailmark बारकोड को कम से कम 90 दिनों के लिए अद्वितीय रूप से पहचाने जाने हेतु एक ID लेनी आवश्यक है। अधिकतम मान: 99999999।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। एरिया (1 या 2 अक्षर) डिस्ट्रिक्ट (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को वैध PAF® फ़ॉर्मेट के अनुरूप होना चाहिए। अधिकतम लंबाई 9 है।

**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


डिलीवरी पते के पोस्टकोड को DPS के साथ शामिल करता है। यदि अंतर्देशीय है तो पोस्टकोड/DP में निम्नलिखित संख्या के अक्षर होते हैं। एरिया (1 या 2 अक्षर) डिस्ट्रिक्ट (1 या 2 अक्षर) सेक्टर (1 अक्षर) यूनिट (2 अक्षर) DPS (2 अक्षर)। पोस्टकोड और DPS को वैध PAF® फ़ॉर्मेट के अनुरूप होना चाहिए। अधिकतम लंबाई 9 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


वह फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। अधिकतम लंबाई 1 है।

**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


वह फ़्लैग जो दर्शाता है कि किस स्तर की Return to Sender सेवा का अनुरोध किया गया है। अधिकतम लंबाई 1 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं। PC (बिना DPS के) को PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


Return to Sender पोस्ट कोड को शामिल करता है लेकिन DPS नहीं। PC (बिना DPS के) को PAF® फ़ॉर्मेट के अनुरूप होना चाहिए।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान।

--------------------

प्रकार के अनुसार अधिकतम लंबाई [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 अक्षर Type 9: 45 अक्षर Type 29: 25 अक्षर

**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


ग्राहक द्वारा उपयोग के लिए वैकल्पिक स्थान।

--------------------

प्रकार के अनुसार अधिकतम लंबाई [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 अक्षर Type 9: 45 अक्षर Type 29: 25 अक्षर

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


DataMatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40। [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


DataMatrix बारकोड का एन्कोड मोड। डिफ़ॉल्ट मान: DataMatrixEncodeMode.C40। [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark Type Data Matrix बारकोड का आकार निर्धारित करता है।

**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark Type Data Matrix बारकोड का आकार निर्धारित करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।

**Returns:**
java.lang.Object
