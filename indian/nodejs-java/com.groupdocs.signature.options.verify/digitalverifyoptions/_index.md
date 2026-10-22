---
title: "DigitalVerifyOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "दस्तावेज़ डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

दस्तावेज़ डिजिटल हस्ताक्षर को सत्यापित करने के विकल्प रखता है।

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | डिफ़ॉल्ट मानों के साथ Digital Verification Option बनाता है। |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | दिए गए डिजिटल प्रमाणपत्र guid के साथ Digital Verification Option बनाता है। |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | दिए गए प्रमाणपत्र स्ट्रीम के साथ Digital Verification Option बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getCertificate()](#getCertificate--) | Certificate Guid या Stream से X509Certificate2 Certificate प्राप्त करें। |
| [getPassword()](#getPassword--) | यदि आवश्यक हो तो Digital Certificate का पासवर्ड। |
| [setPassword(String value)](#setPassword-java.lang.String-) | यदि आवश्यक हो तो Digital Certificate का पासवर्ड। |
| [getCertificateFilePath()](#getCertificateFilePath--) | Digital Certificate का फ़ाइल guid। |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Digital Certificate का फ़ाइल guid। |
| [getCertificateStream()](#getCertificateStream--) | Digital Certificate की स्ट्रीम। |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Digital Certificate की स्ट्रीम। |
| [getComments()](#getComments--) | सत्यापित करने के लिए Digital Signature की टिप्पणियाँ। |
| [setComments(String value)](#setComments-java.lang.String-) | सत्यापित करने के लिए Digital Signature की टिप्पणियाँ। |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। |
| [getReason()](#getReason--) | सत्यापित करने के लिए Digital Signature का कारण। |
| [setReason(String value)](#setReason-java.lang.String-) | सत्यापित करने के लिए Digital Signature का कारण। |
| [getContact()](#getContact--) | सत्यापित करने के लिए Signature संपर्क। |
| [setContact(String value)](#setContact-java.lang.String-) | सत्यापित करने के लिए Signature संपर्क। |
| [getLocation()](#getLocation--) | सत्यापित करने के लिए Signature स्थान। |
| [setLocation(String value)](#setLocation-java.lang.String-) | सत्यापित करने के लिए Signature स्थान। |
| [getSubjectName()](#getSubjectName--) | सत्यापित करने के लिए प्रमाणपत्र का Subject distinguished name। |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | सत्यापित करने के लिए प्रमाणपत्र का Subject distinguished name। |
| [getIssuerName()](#getIssuerName--) | सत्यापित करने के लिए प्रमाणपत्र का Issuer नाम। |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | सत्यापित करने के लिए प्रमाणपत्र का Issuer नाम। |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


डिफ़ॉल्ट मानों के साथ Digital Verification Option बनाता है।

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


दिए गए डिजिटल प्रमाणपत्र guid के साथ Digital Verification Option बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateGuid | java.lang.String | डिजिटल प्रमाणपत्र का फ़ाइल पथ। |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


दिए गए प्रमाणपत्र स्ट्रीम के साथ Digital Verification Option बनाता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Certificate की स्ट्रीम। |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Certificate Guid या Stream से X509Certificate2 Certificate प्राप्त करें।

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


यदि आवश्यक हो तो Digital Certificate का पासवर्ड।

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


यदि आवश्यक हो तो Digital Certificate का पासवर्ड।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Digital Certificate का फ़ाइल guid।

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Digital Certificate का फ़ाइल guid।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Digital Certificate की स्ट्रीम।

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Digital Certificate की स्ट्रीम।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


सत्यापित करने के लिए Digital Signature की टिप्पणियाँ।

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


सत्यापित करने के लिए Digital Signature की टिप्पणियाँ।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। Nullable मान को नजरअंदाज किया जाएगा।

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। Nullable मान को नजरअंदाज किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। Nullable मान को नजरअंदाज किया जाएगा।

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


सत्यापित करने के लिए Digital Signature की तिथि और समय सीमा। Nullable मान को नजरअंदाज किया जाएगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


सत्यापित करने के लिए Digital Signature का कारण।

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


सत्यापित करने के लिए Digital Signature का कारण।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


सत्यापित करने के लिए Signature संपर्क।

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


सत्यापित करने के लिए Signature संपर्क।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


सत्यापित करने के लिए Signature स्थान।

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


सत्यापित करने के लिए Signature स्थान।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


सत्यापित करने के लिए प्रमाणपत्र का Subject distinguished name। मान केस-सेंसिटिव है। यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि Signature का subject name पास किए गए मान को शामिल करता है या उसके बराबर है।

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


सत्यापित करने के लिए प्रमाणपत्र का Subject distinguished name। मान केस-सेंसिटिव है। यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि Signature का subject name पास किए गए मान को शामिल करता है या उसके बराबर है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


सत्यापित करने के लिए प्रमाणपत्र का Issuer नाम। मान केस-सेंसिटिव है। यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि Signature का issuer name पास किए गए मान को शामिल करता है या उसके बराबर है।

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


सत्यापित करने के लिए प्रमाणपत्र का Issuer नाम। मान केस-सेंसिटिव है। यदि यह प्रॉपर्टी सेट की गई है, तो सत्यापन जांचेगा कि Signature का issuer name पास किए गए मान को शामिल करता है या उसके बराबर है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

