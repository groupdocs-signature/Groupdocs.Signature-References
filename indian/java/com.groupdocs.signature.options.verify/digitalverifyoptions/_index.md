---
title: "DigitalVerifyOptions"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "दस्तावेज़ डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

दस्तावेज़ डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | डिफ़ॉल्ट मानों के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है। |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | दिए गए डिजिटल प्रमाणपत्र GUID के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है। |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | दिए गए प्रमाणपत्र स्ट्रीम के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Certificate GUID या स्ट्रीम से X509Certificate2 प्रमाणपत्र प्राप्त करें। |
|
|  | [getPassword()](#getPassword--) | यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड। |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड। |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | डिजिटल प्रमाणपत्र का फ़ाइल GUID। |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | डिजिटल प्रमाणपत्र का फ़ाइल GUID। |
|
|  | [getCertificateStream()](#getCertificateStream--) | डिजिटल प्रमाणपत्र की स्ट्रीम। |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | डिजिटल प्रमाणपत्र की स्ट्रीम। |
|
|  | [getComments()](#getComments--) | मान्य करने के लिए डिजिटल हस्ताक्षर की टिप्पणियाँ। |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | मान्य करने के लिए डिजिटल हस्ताक्षर की टिप्पणियाँ। |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | मान्य करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | मान्य करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | मान्य करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | मान्य करने के लिए डिजिटल हस्ताक्षर की तिथि और समय सीमा। |
|
|  | [getReason()](#getReason--) | मान्य करने के लिए डिजिटल हस्ताक्षर का कारण। |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | मान्य करने के लिए डिजिटल हस्ताक्षर का कारण। |
|
|  | [getContact()](#getContact--) | मान्य करने के लिए हस्ताक्षर संपर्क। |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | मान्य करने के लिए हस्ताक्षर संपर्क। |
|
|  | [getLocation()](#getLocation--) | मान्य करने के लिए हस्ताक्षर स्थान। |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | मान्य करने के लिए हस्ताक्षर स्थान। |
|
|  | [getSubjectName()](#getSubjectName--) | मान्य करने के लिए प्रमाणपत्र का सब्जेक्ट डिस्टिंग्विश्ड नाम। |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | मान्य करने के लिए प्रमाणपत्र का सब्जेक्ट डिस्टिंग्विश्ड नाम। |
|
|  | [getIssuerName()](#getIssuerName--) | मान्य करने के लिए प्रमाणपत्र का जारीकर्ता नाम। |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | मान्य करने के लिए प्रमाणपत्र का जारीकर्ता नाम। |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है।


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


दिए गए डिजिटल प्रमाणपत्र GUID के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | डिजिटल प्रमाणपत्र का फ़ाइल पथ। |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


दिए गए प्रमाणपत्र स्ट्रीम के साथ डिजिटल वेरिफिकेशन विकल्प बनाता है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | प्रमाणपत्र की स्ट्रीम। |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Certificate GUID या स्ट्रीम से X509Certificate2 प्रमाणपत्र प्राप्त करें।


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड।


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


यदि आवश्यक हो तो डिजिटल प्रमाणपत्र का पासवर्ड।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


डिजिटल प्रमाणपत्र का फ़ाइल GUID।


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


डिजिटल प्रमाणपत्र का फ़ाइल GUID।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


डिजिटल प्रमाणपत्र की स्ट्रीम।


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


डिजिटल प्रमाणपत्र की स्ट्रीम।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


मान्य करने के लिए डिजिटल हस्ताक्षर की टिप्पणियाँ।


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


मान्य करने के लिए डिजिटल हस्ताक्षर की टिप्पणियाँ।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


डिजिटल हस्ताक्षर को सत्यापित करने की तिथि और समय सीमा। शून्य मान को नजरअंदाज किया जाएगा।


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


डिजिटल हस्ताक्षर को सत्यापित करने की तिथि और समय सीमा। शून्य मान को नजरअंदाज किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


डिजिटल हस्ताक्षर को सत्यापित करने की तिथि और समय सीमा। शून्य मान को नजरअंदाज किया जाएगा।


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


डिजिटल हस्ताक्षर को सत्यापित करने की तिथि और समय सीमा। शून्य मान को नजरअंदाज किया जाएगा।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


मान्य करने के लिए डिजिटल हस्ताक्षर का कारण।


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


मान्य करने के लिए डिजिटल हस्ताक्षर का कारण।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


मान्य करने के लिए हस्ताक्षर संपर्क।


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


मान्य करने के लिए हस्ताक्षर संपर्क।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


मान्य करने के लिए हस्ताक्षर स्थान।


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


मान्य करने के लिए हस्ताक्षर स्थान।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


प्रमाणपत्र को सत्यापित करने के लिए विषय का विशिष्ट नाम। मान केस-सेंसिटिव है।
यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि हस्ताक्षर विषय नाम में पास किया गया मान शामिल है या बराबर है।


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


प्रमाणपत्र को सत्यापित करने के लिए विषय का विशिष्ट नाम। मान केस-सेंसिटिव है।
यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि हस्ताक्षर विषय नाम में पास किया गया मान शामिल है या बराबर है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


प्रमाणपत्र को सत्यापित करने के लिए जारीकर्ता का नाम। मान केस-सेंसिटिव है।
यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि हस्ताक्षर के जारीकर्ता नाम में पास किया गया मान शामिल है या बराबर है।


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


प्रमाणपत्र को सत्यापित करने के लिए जारीकर्ता का नाम। मान केस-सेंसिटिव है।
यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि हस्ताक्षर के जारीकर्ता नाम में पास किया गया मान शामिल है या बराबर है।


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

