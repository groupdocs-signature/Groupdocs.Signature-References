---
title: DigitalSignOptions
second_title: GroupDocs.Signature for Java API Reference
description: Represents the Digital signature options.
type: docs
weight: 11
url: /java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

Represents the Digital signature options.
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignOptions()](#DigitalSignOptions--) | Initializes a new instance of the DigitalSignOptions class with default values. |
| [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | Initializes a new instance of the DigitalSignOptions class with certificate file. |
| [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | Initializes a new instance of the DigitalSignOptions class with certificate stream. |
| [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | Initializes a new instance of the DigitalSignOptions class with certificate file and image file. |
| [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | Initializes a new instance of the DigitalSignOptions class with certificate file and image stream. |
| [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image file. |
| [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | Initializes a new instance of the DigitalSignOptions class with certificate stream and image stream. |
## Methods

| Method | Description |
| --- | --- |
| [getReason()](#getReason--) | Gets or sets the reason of signature. |
| [setReason(String value)](#setReason-java.lang.String-) | Gets or sets the reason of signature. |
| [getContact()](#getContact--) | Gets or sets the signature contact. |
| [setContact(String value)](#setContact-java.lang.String-) | Gets or sets the signature contact. |
| [getLocation()](#getLocation--) | Gets or sets the signature location. |
| [setLocation(String value)](#setLocation-java.lang.String-) | Gets or sets the signature location. |
| [getPassword()](#getPassword--) | Gets or sets the password of digital certificate. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Gets or sets the password of digital certificate. |
| [getSignature()](#getSignature--) | Gets or sets properties of document digital signature. |
| [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | Gets or sets properties of document digital signature. |
| [getCertificateFilePath()](#getCertificateFilePath--) | Gets or sets the digital certificate file path. |
| [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Gets or sets the digital certificate file GUID. |
| [getCertificateStream()](#getCertificateStream--) | Gets or sets digital certificate stream. |
| [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Gets or sets digital certificate stream. |
| [getVisible()](#getVisible--) | Gets or sets the visibility of signature. |
| [setVisible(boolean value)](#setVisible-boolean-) | Gets or sets the visibility of signature. |
| [getXAdESType()](#getXAdESType--) | XAdES type  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES type  XAdESType . |
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
| [toString()](#toString--) | Override string conversion. |
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


Initializes a new instance of the DigitalSignOptions class with default values.

### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


Initializes a new instance of the DigitalSignOptions class with certificate file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Digital certificate file path |

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


Initializes a new instance of the DigitalSignOptions class with certificate stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Digital Certificate stream |

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


Initializes a new instance of the DigitalSignOptions class with certificate file and image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Digital certificate file path |
| imageFilePath | java.lang.String | Signature Appearance image file path |

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


Initializes a new instance of the DigitalSignOptions class with certificate file and image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateFilePath | java.lang.String | Digital certificate file path |
| appearenceImageStream | java.io.InputStream | Signature Appearance image stream |

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


Initializes a new instance of the DigitalSignOptions class with certificate stream and image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Digital Certificate stream |
| imageFilePath | java.lang.String | Signature Appearance image file path |

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


Initializes a new instance of the DigitalSignOptions class with certificate stream and image stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificateStream | java.io.InputStream | Digital Certificate stream |
| appearenceImageStream | java.io.InputStream | Signature Appearance image stream |

### getReason() {#getReason--}
```
public final String getReason()
```


Gets or sets the reason of signature.

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


Gets or sets the reason of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


Gets or sets the signature contact.

**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


Gets or sets the signature contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


Gets or sets the signature location.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


Gets or sets the signature location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


Gets or sets the password of digital certificate.

**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


Gets or sets the password of digital certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


Gets or sets properties of document digital signature.

**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


Gets or sets properties of document digital signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Gets or sets the digital certificate file path. This property is used only if CertificateStream is not specified.

**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


Gets or sets the digital certificate file GUID. This property is used only if CertificateStream is not specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Gets or sets digital certificate stream. If this property is specified it is always used instead CertificateGuid.

**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Gets or sets digital certificate stream. If this property is specified it is always used instead CertificateGuid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Gets or sets the visibility of signature.

**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Gets or sets the visibility of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES type  XAdESType . Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents under .NET Framework only (not under .NET Standard)

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES type  XAdESType . Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents under .NET Framework only (not under .NET Standard)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
