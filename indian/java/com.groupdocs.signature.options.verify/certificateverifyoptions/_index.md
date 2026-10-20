---
title: "CertificateVerifyOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "प्रमाणपत्र दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 11
url: /hi/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

प्रमाणपत्र दस्तावेज़ों को सत्यापित करने के विकल्प रखता है।

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | डिफ़ॉल्ट मानों के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है। |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | CertificateVerifyOptions का एक नया इंस्टेंस प्रारंभ करता है जिसमें सत्यापित करने के लिए विषय शामिल है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें। |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें। |
|
|  | [getSerialNumber()](#getSerialNumber--) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र सीरियल नंबर निर्दिष्ट करें। |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र सीरियल नंबर निर्दिष्ट करें। |
|
|  | [getSubject()](#getSubject--) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें। |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें। |
|
|  | [getThumbprint()](#getThumbprint--) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र थंबप्रिंट निर्दिष्ट करें। |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र थंबप्रिंट निर्दिष्ट करें। |
|
|  | [getMatchType()](#getMatchType--) | टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
|
|  | [setMatchType(int value)](#setMatchType-int-) | टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है। |
|
|  | [getExpired()](#getExpired--) | सत्यापन परिणाम के कारण यदि प्रमाणपत्र की समाप्ति तिथि है तो दर्शाता है। |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | सत्यापन परिणाम के कारण यदि प्रमाणपत्र की समाप्ति तिथि है तो दर्शाता है। |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | यदि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए तो प्राप्त करें या सेट करें। |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | यदि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए तो प्राप्त करें या सेट करें। |
|
|  | [toString()](#toString--) | स्ट्रिंग में रूपांतरण को ओवरराइड करता है। |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ TextVerifyOptions का नया इंस्टेंस प्रारंभ करता है।


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


CertificateVerifyOptions का एक नया इंस्टेंस प्रारंभ करता है जिसमें सत्यापित करने के लिए विषय शामिल है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | विषय | java.lang.String | सत्यापित करने के लिए विषय |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें।


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र जारीकर्ता निर्दिष्ट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र सीरियल नंबर निर्दिष्ट करें।


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र सीरियल नंबर निर्दिष्ट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें।


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र विषय निर्दिष्ट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र थंबप्रिंट निर्दिष्ट करें।


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


यदि सत्यापित किया जाना चाहिए तो प्रमाणपत्र थंबप्रिंट निर्दिष्ट करें।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है।


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


टेक्स्ट मैच टाइप सत्यापन को प्राप्त करता है या सेट करता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


सत्यापन परिणाम के कारण यदि प्रमाणपत्र की समाप्ति तिथि है तो दर्शाता है।
प्रॉपर्टी केवल पढ़ने योग्य है।


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


सत्यापन परिणाम के कारण यदि प्रमाणपत्र की समाप्ति तिथि है तो दर्शाता है।
प्रॉपर्टी केवल पढ़ने योग्य है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


यदि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए तो प्राप्त करें या सेट करें।
डिफ़ॉल्ट रूप से यह मान true है।


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


यदि सत्यापन प्रक्रिया को बेसिक वैलिडेशन पॉलिसी का उपयोग करके X.509 चेन वैलिडेशन प्रदान करना चाहिए तो प्राप्त करें या सेट करें।
डिफ़ॉल्ट रूप से यह मान true है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | boolean |  |

### toString() {#toString--}
```
public String toString()
```


स्ट्रिंग में रूपांतरण को ओवरराइड करता है।


**Returns:**
java.lang.String -
