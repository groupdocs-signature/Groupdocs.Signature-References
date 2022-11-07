---
title: DigitalSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Digital signature properties.
type: docs
weight: 12
url: /java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

Contains Digital signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignature()](#DigitalSignature--) | Initialize Digital signature with default parameters. |
| [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | Initialize Digital signature with known SignatureId. |
| [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | Create Digital signature with specified certificate. |
## Methods

| Method | Description |
| --- | --- |
| [getCertificate()](#getCertificate--) | Gets or sets the X509 certificate. |
| [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | Gets or sets the X509 certificate. |
| [getComments()](#getComments--) | Gets or sets the signing purpose comment. |
| [setComments(String value)](#setComments-java.lang.String-) | Gets or sets the signing purpose comment. |
| [isValid()](#isValid--) | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [setValid(boolean value)](#setValid-boolean-) | Keeps true if this digital signature is valid and the document has not been tampered with. |
| [getSignTime()](#getSignTime--) | Gets or sets the time the document was signed. |
| [setSignTime(Date value)](#setSignTime-java.util.Date-) | Gets or sets the time the document was signed. |
| [getXAdESType()](#getXAdESType--) | XAdES type  XAdESType . |
| [setXAdESType(int value)](#setXAdESType-int-) | XAdES type  XAdESType . |
| [getThumbprint()](#getThumbprint--) | Gets the thumbprint of a certificate. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Barcode Signature instance. |
| [loadDigitalSignatures()](#loadDigitalSignatures--) | Load Digital signature from all system X509 Certificates Stores. |
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


Initialize Digital signature with default parameters.

### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


Initialize Digital signature with known SignatureId.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


Create Digital signature with specified certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | java.security.KeyStore | X509 certificate. |

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


Gets or sets the X509 certificate.

**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


Gets or sets the X509 certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.security.KeyStore |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Gets or sets the signing purpose comment.

**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Gets or sets the signing purpose comment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


Keeps true if this digital signature is valid and the document has not been tampered with.

**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


Keeps true if this digital signature is valid and the document has not been tampered with.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


Gets or sets the time the document was signed.

**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


Gets or sets the time the document was signed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES type  XAdESType . Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents.

**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES type  XAdESType . Default value is None (XAdES is off). At this moment XAdES signature type is supported only for Spreadsheet documents.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


Gets the thumbprint of a certificate.

**Returns:**
java.lang.String
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


Overwrites Equals method to compare signature properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | java.lang.Object | Signature object to compare with. |

**Returns:**
boolean - Returns true if passed signature object has same type and all its properties are equal to this instance properties.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Overrides GetHashCode method

**Returns:**
int - Signature hash code
### deepClone() {#deepClone--}
```
public Object deepClone()
```


Clone Barcode Signature instance.

**Returns:**
java.lang.Object - Returns cloned Barcode Signature instance.
### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


Load Digital signature from all system X509 Certificates Stores.

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - Returns list of [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) Digital Signatures.
