---
title: "EPC"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "यूरोपीय भुगतान परिषद क्विक रिस्पॉन्स कोड दर्शाता है।"
type: docs
weight: 14
url: /hi/nodejs-java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

यूरोपीय भुगतान परिषद क्विक रिस्पॉन्स कोड दर्शाता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [EPC()](#EPC--) | नया EPC ऑब्जेक्ट इंस्टैंशिएट करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getName()](#getName--) | लाभार्थी का नाम प्राप्त करता है या सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | लाभार्थी का नाम प्राप्त करता है या सेट करता है। |
| [getBIC()](#getBIC--) | लाभार्थी का BIC प्राप्त करता है या सेट करता है, जिसकी अधिकतम लंबाई 11 अक्षर है। |
| [setBIC(String value)](#setBIC-java.lang.String-) | लाभार्थी का BIC प्राप्त करता है या सेट करता है, जिसकी अधिकतम लंबाई 11 अक्षर है। |
| [getIBAN()](#getIBAN--) | लाभार्थी का खाता (IBAN) प्राप्त करता है या सेट करता है। |
| [setIBAN(String value)](#setIBAN-java.lang.String-) | लाभार्थी का खाता (IBAN) प्राप्त करता है या सेट करता है। |
| [getAmount()](#getAmount--) | राशि प्राप्त करता है या सेट करता है। |
| [setAmount(double value)](#setAmount-double-) | राशि प्राप्त करता है या सेट करता है। |
| [getCode()](#getCode--) | व्यवसाय कोड प्राप्त करता है या सेट करता है, अधिकतम 4 अक्षर। |
| [setCode(String value)](#setCode-java.lang.String-) | व्यवसाय कोड प्राप्त करता है या सेट करता है, अधिकतम 4 अक्षर। |
| [getReference()](#getReference--) | भुगतान संदर्भ प्राप्त करता है या सेट करता है (अधिकतम 35 अक्षर)। |
| [setReference(String value)](#setReference-java.lang.String-) | भुगतान संदर्भ प्राप्त करता है या सेट करता है (अधिकतम 35 अक्षर)। |
| [getRemittance()](#getRemittance--) | रिमिटेंस जानकारी प्राप्त करता है या सेट करता है (अधिकतम 140 अक्षर)। |
| [setRemittance(String value)](#setRemittance-java.lang.String-) | रिमिटेंस जानकारी प्राप्त करता है या सेट करता है (अधिकतम 140 अक्षर)। |
| [getInformation()](#getInformation--) | संकेत जानकारी प्राप्त करता है या सेट करता है। |
| [setInformation(String value)](#setInformation-java.lang.String-) | संकेत जानकारी प्राप्त करता है या सेट करता है। |
| [getVersion()](#getVersion--) | EPC / SEPA QR-कोड संस्करण कार्यान्वयन। |
| [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-कोड संस्करण कार्यान्वयन। |
| [getCharset()](#getCharset--) | EPC / SEPA QR-कोड कैरेक्टर सेट कार्यान्वयन। |
| [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-कोड कैरेक्टर सेट कार्यान्वयन। |
| [getIdentification()](#getIdentification--) | EPC / SEPA QR-कोड पहचान। |
| [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-कोड पहचान। |
| [equals(Object source)](#equals-java.lang.Object-) | EPC गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
### EPC() {#EPC--}
```
public EPC()
```


नया EPC ऑब्जेक्ट इंस्टैंशिएट करता है।

### getName() {#getName--}
```
public final String getName()
```


लाभार्थी का नाम प्राप्त करता है या सेट करता है। अधिकतम लंबाई 70 अक्षर है।

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


लाभार्थी का नाम प्राप्त करता है या सेट करता है। अधिकतम लंबाई 70 अक्षर है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


लाभार्थी का BIC प्राप्त करता है या सेट करता है, जिसकी अधिकतम लंबाई 11 अक्षर है।

**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


लाभार्थी का BIC प्राप्त करता है या सेट करता है, जिसकी अधिकतम लंबाई 11 अक्षर है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


लाभार्थी का खाता (IBAN) प्राप्त करता है या सेट करता है। IBAN अधिकतम 34 अल्फ़ान्यूमेरिक अक्षरों से बना होता है।

**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


लाभार्थी का खाता (IBAN) प्राप्त करता है या सेट करता है। IBAN अधिकतम 34 अल्फ़ान्यूमेरिक अक्षरों से बना होता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


राशि प्राप्त करता है या सेट करता है।

**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


राशि प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


व्यवसाय कोड प्राप्त करता है या सेट करता है, अधिकतम 4 अक्षर।

**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


व्यवसाय कोड प्राप्त करता है या सेट करता है, अधिकतम 4 अक्षर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


भुगतान संदर्भ प्राप्त करता है या सेट करता है (अधिकतम 35 अक्षर)। यह फ़ील्ड और रिमिटेंस जानकारी फ़ील्ड परस्पर अनन्य हैं।

**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


भुगतान संदर्भ प्राप्त करता है या सेट करता है (अधिकतम 35 अक्षर)। यह फ़ील्ड और रिमिटेंस जानकारी फ़ील्ड परस्पर अनन्य हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


रिमिटेंस जानकारी प्राप्त करता है या सेट करता है (अधिकतम 140 अक्षर)। यह फ़ील्ड और भुगतान संदर्भ फ़ील्ड परस्पर अनन्य हैं।

**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


रिमिटेंस जानकारी प्राप्त करता है या सेट करता है (अधिकतम 140 अक्षर)। यह फ़ील्ड और भुगतान संदर्भ फ़ील्ड परस्पर अनन्य हैं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


संकेत जानकारी प्राप्त करता है या सेट करता है। अधिकतम 70 अक्षर।

**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


संकेत जानकारी प्राप्त करता है या सेट करता है। अधिकतम 70 अक्षर।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code संस्करण कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 002 पर सेट किया गया है।

**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code संस्करण कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 002 पर सेट किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code अक्षर सेट कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 1 पर सेट किया गया है।

**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code अक्षर सेट कार्यान्वयन। डिफ़ॉल्ट रूप से यह मान 1 पर सेट किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code पहचान। डिफ़ॉल्ट रूप से यह मान SCT पर सेट किया गया है।

**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code पहचान। डिफ़ॉल्ट रूप से यह मान SCT पर सेट किया गया है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


EPC गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| स्रोत | java.lang.Object | तुलना करने के लिए EPC ऑब्जेक्ट। |

**Returns:**
boolean - true लौटाता है यदि पास किया गया पता ऑब्जेक्ट समान प्रकार का है और उसकी सभी प्रॉपर्टी इस इंस्टेंस की प्रॉपर्टी के बराबर हैं।
### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode मेथड को ओवरराइड करता है।

**Returns:**
int - ईमेल हैश कोड
