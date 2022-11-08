---
title: DigitalSignatureAppearance
second_title: GroupDocs.Signature for Java API Reference
description: Describes appearance of Signature Line for Digital Signature.
type: docs
weight: 10
url: /java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

Describes appearance of Signature Line for Digital Signature. One Signature Line could be applied for only one Digital Signature. Signature Line always is on the first page. This feature may be useful for .docx, .doc, .odt and .xlsx file formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Creates Signature Line Appearance object. |
| [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | Creates Signature Line Appearance with specified values (signer, title, email). |
## Methods

| Method | Description |
| --- | --- |
| [getSigner()](#getSigner--) | Gets or sets signer name for signature line. |
| [setSigner(String value)](#setSigner-java.lang.String-) | Gets or sets signer name for signature line. |
| [getTitle()](#getTitle--) | Gets or sets a title for signature line. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Gets or sets a title for signature line. |
| [getEmail()](#getEmail--) | Gets or sets a email that will be displayed in signature line. |
| [setEmail(String value)](#setEmail-java.lang.String-) | Gets or sets a email that will be displayed in signature line. |
| [toString()](#toString--) | Override string conversion. |
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Creates Signature Line Appearance object.

### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


Creates Signature Line Appearance with specified values (signer, title, email).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signer | java.lang.String | Signer name. |
| title | java.lang.String | Signature title. |
| email | java.lang.String | Author' email. |

### getSigner() {#getSigner--}
```
public final String getSigner()
```


Gets or sets signer name for signature line.

**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


Gets or sets signer name for signature line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Gets or sets a title for signature line.

**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Gets or sets a title for signature line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


Gets or sets a email that will be displayed in signature line.

**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


Gets or sets a email that will be displayed in signature line.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


Override string conversion.

**Returns:**
java.lang.String - 
