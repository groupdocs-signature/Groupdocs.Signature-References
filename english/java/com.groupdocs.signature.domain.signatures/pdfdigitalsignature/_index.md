---
title: PdfDigitalSignature
second_title: GroupDocs.Editor for Java API Reference
description: Contains Pdf Digital signature properties.
type: docs
weight: 14
url: /java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

Contains Pdf Digital signature properties.
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfDigitalSignature()](#PdfDigitalSignature--) | Initialize Pdf Digital Signature with no certificate. |
| [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | Create Pdf Digital signature with specified certificate. |
## Methods

| Method | Description |
| --- | --- |
| [getContactInfo()](#getContactInfo--) | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. |
| [setContactInfo(String value)](#setContactInfo-java.lang.String-) | Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. |
| [getLocation()](#getLocation--) | The CPU host name or physical location of the signing. |
| [setLocation(String value)](#setLocation-java.lang.String-) | The CPU host name or physical location of the signing. |
| [getReason()](#getReason--) | The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [setReason(String value)](#setReason-java.lang.String-) | The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
| [getType()](#getType--) | Type of Pdf digital signature. |
| [setType(int value)](#setType-int-) | Type of Pdf digital signature. |
| [getTimeStamp()](#getTimeStamp--) | Time stamp for Pdf digital signature. |
| [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Time stamp for Pdf digital signature. |
| [getShowProperties()](#getShowProperties--) | Force to show/hide signature properties. |
| [setShowProperties(boolean value)](#setShowProperties-boolean-) | Force to show/hide signature properties. |
| [equals(Object signature)](#equals-java.lang.Object-) | Overwrites Equals method to compare signature properties |
| [hashCode()](#hashCode--) | Overrides GetHashCode method |
| [deepClone()](#deepClone--) | Clone Barcode Signature instance. |
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


Initialize Pdf Digital Signature with no certificate.

### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


Create Pdf Digital signature with specified certificate.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| certificate | java.security.KeyStore | X509 certificate. |

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


Information provided by the signer to enable a recipient to contact the signer to verify the signature, e.g. a phone number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


The CPU host name or physical location of the signing.

**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


The CPU host name or physical location of the signing.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


The reason for the signing, such as (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Type of Pdf digital signature.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Type of Pdf digital signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Time stamp for Pdf digital signature. Default value is null.

**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Time stamp for Pdf digital signature. Default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date: \{Date\} Reason: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Location: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties is true by default.

**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


Force to show/hide signature properties. In case ShowProperties is true signature field has predefined format of appearance Digitally signed by \{ ContactInfo (\#getContactInfo.getContactInfo/\#setContactInfo(String).setContactInfo(String))\} Date: \{Date\} Reason: \{ Reason (\#getReason.getReason/\#setReason(String).setReason(String))\} Location: \{ Location (\#getLocation.getLocation/\#setLocation(String).setLocation(String))\} ShowProperties is true by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
