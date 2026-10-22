---
title: "DigitalSignature"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Digital signature गुणों को शामिल करता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Digital signature गुणों को शामिल करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DigitalSignature()](#DigitalSignature--) | डिफ़ॉल्ट पैरामीटरों के साथ Digital हस्ताक्षर को प्रारंभ करें। |
| [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | ज्ञात SignatureId के साथ Digital हस्ताक्षर को प्रारंभ करें। |
| [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | निर्दिष्ट प्रमाणपत्र के साथ Digital हस्ताक्षर बनाएं। |
| [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | X509Certificate प्रमाणपत्र और PrivateKey के आधार पर Digital हस्ताक्षर बनाएं। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCertificate()](#getCertificate--) | KeyStore प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | KeyStore प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [getX509Certificate()](#getX509Certificate--) | X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है। |
| [getPrivateKey()](#getPrivateKey--) | प्रमाणपत्र की PrivateKey को प्राप्त करता है या सेट करता है। |
| [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | प्रमाणपत्र की PrivateKey को प्राप्त करता है या सेट करता है। |
| [getCertificateName()](#getCertificateName--) | X509 प्रमाणपत्र का नाम प्राप्त करता है या सेट करता है। |
| [setCertificateName(String value)](#setCertificateName-java.lang.String-) | X509 प्रमाणपत्र का नाम प्राप्त करता है या सेट करता है। |
| [getComments()](#getComments--) | हस्ताक्षर उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है। |
| [setComments(String value)](#setComments-java.lang.String-) | हस्ताक्षर उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है। |
| [isValid()](#isValid--) | यदि यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में छेड़छाड़ नहीं हुई है तो true रखता है। |
| [setValid(boolean value)](#setValid-boolean-) | यदि यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में छेड़छाड़ नहीं हुई है तो true रखता है। |
| [getSignTime()](#getSignTime--) | दस्तावेज़ पर हस्ताक्षर किए जाने का समय प्राप्त करता है या सेट करता है। |
| [setSignTime(Date value)](#setSignTime-java.util.Date-) | दस्तावेज़ पर हस्ताक्षर किए जाने का समय प्राप्त करता है या सेट करता है। |
| [getXAdESType()](#getXAdESType--) | XAdES प्रकार  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES प्रकार  XAdESType . |
| [getThumbprint()](#getThumbprint--) | प्रमाणपत्र का थंबप्रिंट प्राप्त करता है। |
| [equals(Object signature)](#equals-java.lang.Object-) | हस्ताक्षर गुणों की तुलना करने के लिए Equals मेथड को ओवरराइट करता है। |
| [hashCode()](#hashCode--) | GetHashCode मेथड को ओवरराइड करता है। |
| [deepClone()](#deepClone--) | Barcode Signature इंस्टेंस को क्लोन करें। |
| [loadDigitalSignatures()](#loadDigitalSignatures--) | सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से Digital हस्ताक्षर लोड करें। |
| [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | पारित X509 प्रमाणपत्र स्टोर से Digital हस्ताक्षर लोड करें। |
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


डिफ़ॉल्ट पैरामीटरों के साथ Digital हस्ताक्षर को प्रारंभ करें।

### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


ज्ञात SignatureId के साथ Digital हस्ताक्षर को प्रारंभ करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


निर्दिष्ट प्रमाणपत्र के साथ Digital हस्ताक्षर बनाएं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| प्रमाणपत्र | java.security.KeyStore | X509 प्रमाणपत्र। |

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


X509Certificate प्रमाणपत्र और PrivateKey के आधार पर Digital हस्ताक्षर बनाएं।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cert | java.security.cert.X509Certificate | X509Certificate प्रमाणपत्र। |
| कुंजी | java.security.PrivateKey | प्रमाणपत्र की PrivateKey। |

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


KeyStore प्रमाणपत्र को प्राप्त करता है या सेट करता है।

**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


KeyStore प्रमाणपत्र को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है।

**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


X509 प्रमाणपत्र को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


प्रमाणपत्र की PrivateKey को प्राप्त करता है या सेट करता है।

**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


प्रमाणपत्र की PrivateKey को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


X509 प्रमाणपत्र का नाम प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


X509 प्रमाणपत्र का नाम प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


हस्ताक्षर उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है।

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


हस्ताक्षर उद्देश्य टिप्पणी को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


यदि यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में छेड़छाड़ नहीं हुई है तो true रखता है।

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


यदि यह डिजिटल हस्ताक्षर वैध है और दस्तावेज़ में छेड़छाड़ नहीं हुई है तो true रखता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


दस्तावेज़ पर हस्ताक्षर किए जाने का समय प्राप्त करता है या सेट करता है।

**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


दस्तावेज़ पर हस्ताक्षर किए जाने का समय प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES प्रकार XAdESType। डिफ़ॉल्ट मान None है (XAdES बंद है)। इस समय XAdES हस्ताक्षर प्रकार केवल Spreadsheet दस्तावेज़ों के लिए समर्थित है।

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES प्रकार XAdESType। डिफ़ॉल्ट मान None है (XAdES बंद है)। इस समय XAdES हस्ताक्षर प्रकार केवल Spreadsheet दस्तावेज़ों के लिए समर्थित है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


प्रमाणपत्र का थंबप्रिंट प्राप्त करता है।

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


Barcode Signature इंस्टेंस को क्लोन करें।

**Returns:**
java.lang.Object - क्लोन किया गया Barcode Signature इंस्टेंस लौटाता है।
### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


सभी सिस्टम X509 प्रमाणपत्र स्टोर्स से Digital हस्ताक्षर लोड करें।

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - डिजिटल सिग्नेचर की सूची लौटाता है [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digital Signatures.
### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


पारित X509 प्रमाणपत्र स्टोर से Digital हस्ताक्षर लोड करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - डिजिटल सिग्नेचर की सूची लौटाता है [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digital Signatures.
