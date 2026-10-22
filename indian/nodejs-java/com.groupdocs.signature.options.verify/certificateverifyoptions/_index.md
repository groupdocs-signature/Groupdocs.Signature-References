---
title: "CertificateVerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "प्रमाणपत्र दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 11
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

प्रमाणपत्र दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।

--------------------

 **Learn more** 

 *  
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [CertificateVerifyOptions()](#CertificateVerifyOptions--) | डिफ़ॉल्ट मानों के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है। |
| [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | सत्यापित करने के लिए विषय के साथ CertificateVerifyOptions का एक नया उदाहरण प्रारंभ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getIssuer()](#getIssuer--) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें। |
| [setIssuer(String value)](#setIssuer-java.lang.String-) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें। |
| [getSerialNumber()](#getSerialNumber--) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र क्रमांक निर्दिष्ट करें। |
| [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र क्रमांक निर्दिष्ट करें। |
| [getSubject()](#getSubject--) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें। |
| [setSubject(String value)](#setSubject-java.lang.String-) | यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें। |
| [getThumbprint()](#getThumbprint--) | यदि प्रमाणपत्र थंबप्रिंट को सत्यापित किया जाना चाहिए तो निर्दिष्ट करें। |
| [setThumbprint(String value)](#setThumbprint-java.lang.String-) | यदि प्रमाणपत्र थंबप्रिंट को सत्यापित किया जाना चाहिए तो निर्दिष्ट करें। |
| [getMatchType()](#getMatchType--) | Text Match Type सत्यापन को प्राप्त करता है या सेट करता है। |
| [setMatchType(int value)](#setMatchType-int-) | Text Match Type सत्यापन को प्राप्त करता है या सेट करता है। |
| [getExpired()](#getExpired--) | सत्यापन परिणाम के कारण प्रमाणपत्र की समाप्ति तिथि है या नहीं दर्शाता है। |
| [setExpired(boolean value)](#setExpired-boolean-) | सत्यापन परिणाम के कारण प्रमाणपत्र की समाप्ति तिथि है या नहीं दर्शाता है। |
| [getPerformChainValidation()](#getPerformChainValidation--) | प्राप्त करें या सेट करें कि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए या नहीं। |
| [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | प्राप्त करें या सेट करें कि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए या नहीं। |
| [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ TextVerifyOptions का एक नया उदाहरण प्रारंभ करता है।

### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


सत्यापित करने के लिए विषय के साथ CertificateVerifyOptions का एक नया उदाहरण प्रारंभ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| विषय | java.lang.String | सत्यापित करने योग्य विषय |

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें।

**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र क्रमांक निर्दिष्ट करें।

**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र क्रमांक निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें।

**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


यदि इसे सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


यदि प्रमाणपत्र थंबप्रिंट को सत्यापित किया जाना चाहिए तो निर्दिष्ट करें।

**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


यदि प्रमाणपत्र थंबप्रिंट को सत्यापित किया जाना चाहिए तो निर्दिष्ट करें।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Text Match Type सत्यापन को प्राप्त करता है या सेट करता है।

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Text Match Type सत्यापन को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


सत्यापन परिणाम के कारण प्रमाणपत्र की समाप्ति तिथि है या नहीं दर्शाता है। यह प्रॉपर्टी केवल-रिड है।

**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


सत्यापन परिणाम के कारण प्रमाणपत्र की समाप्ति तिथि है या नहीं दर्शाता है। यह प्रॉपर्टी केवल-रिड है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


प्राप्त करें या सेट करें कि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए या नहीं। डिफ़ॉल्ट रूप से यह मान true है।

**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


प्राप्त करें या सेट करें कि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए या नहीं। डिफ़ॉल्ट रूप से यह मान true है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।

**Returns:**
java.lang.String -
