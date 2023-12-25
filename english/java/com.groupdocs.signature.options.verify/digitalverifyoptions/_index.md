---
title: DigitalVerifyOptions
second_title: GroupDocs.Signature for Java API Reference
description: Keeps options to verify document Digital signature.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

Keeps options to verify document Digital signature.

--------------------

**Learn more**

 *  Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document ][How to eVerification Digital signatures in a document]
 *  Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: Advanced usage of eVerification Digital signatures in a document and additional settings


[How to eVerification Digital signatures in a document]: https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalVerifyOptions()](#DigitalVerifyOptions--) | Creates Digital Verification Option with default values. |
| [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | Creates Digital Verification Option with given digital certificate guid. |
| [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | Creates Digital Verification Option with given certificate stream. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Get X509Certificate2 Certificate from Certificate Guid or Stream. |
| [getPassword()](#getPassword--) | Password of Digital Certificate if required. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Password of Digital Certificate if required. |
| [getCertificateFilePath()](#getCertificateFilePath--) | File Guid of Digital Certificate. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | File Guid of Digital Certificate. |
| [getCertificateStream()](#getCertificateStream--) | Stream of Digital Certificate. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Stream of Digital Certificate. |
| [getComments()](#getComments--) | Comments of Digital Signature to validate. |
| [setComments(String value)](#setComments-java.lang.String-) | Comments of Digital Signature to validate. |
| [getSignDateTimeFrom()](#getSignDateTimeFrom--) | Date and time range of Digital Signature to validate. |
| [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | Date and time range of Digital Signature to validate. |
| [getSignDateTimeTo()](#getSignDateTimeTo--) | Date and time range of Digital Signature to validate. |
| [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | Date and time range of Digital Signature to validate. |
| [getReason()](#getReason--) | Reason of Digital Signature to validate. |
| [setReason(String value)](#setReason-java.lang.String-) | Reason of Digital Signature to validate. |
| [getContact()](#getContact--) | Signature Contact to validate. |
| [setContact(String value)](#setContact-java.lang.String-) | Signature Contact to validate. |
| [getLocation()](#getLocation--) | Signature Location to validate. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Signature Location to validate. |
| [getSubjectName()](#getSubjectName--) | Subject distinguished name of the certificate to validate. |
| [setSubjectName(String value)](#setSubjectName-java.lang.String-) | Subject distinguished name of the certificate to validate. |
| [getIssuerName()](#getIssuerName--) | Issuer name of the certificate to validate. |
| [setIssuerName(String value)](#setIssuerName-java.lang.String-) | Issuer name of the certificate to validate. |
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


Creates Digital Verification Option with default values.

### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


Creates Digital Verification Option with given digital certificate guid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateGuid | java.lang.String | File path to digital certificate. |

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


Creates Digital Verification Option with given certificate stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Certificate's stream. |

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Get X509Certificate2 Certificate from Certificate Guid or Stream.

**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


Password of Digital Certificate if required.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Password of Digital Certificate if required.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


File Guid of Digital Certificate.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


File Guid of Digital Certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Stream of Digital Certificate.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Stream of Digital Certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Comments of Digital Signature to validate.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Comments of Digital Signature to validate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


Date and time range of Digital Signature to validate. Nullable value will be ignored.

**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


Date and time range of Digital Signature to validate. Nullable value will be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


Date and time range of Digital Signature to validate. Nullable value will be ignored.

**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


Date and time range of Digital Signature to validate. Nullable value will be ignored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


Reason of Digital Signature to validate.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Reason of Digital Signature to validate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Signature Contact to validate.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Signature Contact to validate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Signature Location to validate.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Signature Location to validate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


Subject distinguished name of the certificate to validate. Value is case sensitive. If this property is set verification will check if Signature subject name contains or equals passed value

**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


Subject distinguished name of the certificate to validate. Value is case sensitive. If this property is set verification will check if Signature subject name contains or equals passed value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


Issuer name of the certificate to validate. Value is case sensitive. If this property is set verification will check if Signature's issuer name contains or equals passed value

**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


Issuer name of the certificate to validate. Value is case sensitive. If this property is set verification will check if Signature's issuer name contains or equals passed value

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

