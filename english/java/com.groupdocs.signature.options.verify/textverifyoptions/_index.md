---
title: TextVerifyOptions
second_title: GroupDocs.Signature for Java API Reference
description: Keeps options to verify document Text signature.
type: docs
weight: 14
url: /java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

Keeps options to verify document Text signature.

--------------------

**Learn more**

 *  Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document ][How to eVerification QR-code signatures in a document]
 *  Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings][]


[How to eVerification QR-code signatures in a document]: https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/
[Advanced usage of eVerification Barcode signatures in a document and additional settings]: https://docs.groupdocs.com/signature/java/verify-text-signatures/
## Constructors

| Constructor | Description |
| --- | --- |
| [TextVerifyOptions()](#TextVerifyOptions--) | Initializes a new instance of the TextVerifyOptions with default values. |
| [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | Initializes a new instance of the TextVerifyOptions with verification text. |
| [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | Initializes a new instance of the TextVerifyOptions with Text property to verify and signature implementation. |
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | Specify Signature Text if it should be verified. |
| [setText(String value)](#setText-java.lang.String-) | Specify Signature Text if it should be verified. |
| [getMatchType()](#getMatchType--) | Gets or sets Text Match Type verification. |
| [setMatchType(int value)](#setMatchType-int-) | Gets or sets Text Match Type verification. |
| [getSignatureImplementation()](#getSignatureImplementation--) | Type of Signature to be verified. |
| [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | Type of Signature to be verified. |
| [getFormTextFieldTitle()](#getFormTextFieldTitle--) | Gets or sets the title of form field to verify it. |
| [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | Gets or sets the title of form field to verify it. |
| [getFormTextFieldType()](#getFormTextFieldType--) | Gets or sets the type of form field to verify it. |
| [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | Gets or sets the type of form field to verify it. |
| [getSignatureID()](#getSignatureID--) | Specify Text Signature ID more than zero if it should be verified. |
| [setSignatureID(int value)](#setSignatureID-int-) | Specify Text Signature ID more than zero if it should be verified. |
| [toString()](#toString--) | Overrides conversion to string. |
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


Initializes a new instance of the TextVerifyOptions with default values.

### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


Initializes a new instance of the TextVerifyOptions with verification text.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to be verified |

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


Initializes a new instance of the TextVerifyOptions with Text property to verify and signature implementation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text to be verified. |
| implementation | int | Signature Implementation type. |

### getText() {#getText--}
```
public final String getText()
```


Specify Signature Text if it should be verified.

**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Specify Signature Text if it should be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Gets or sets Text Match Type verification.

**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Gets or sets Text Match Type verification.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


Type of Signature to be verified.

**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


Type of Signature to be verified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


Gets or sets the title of form field to verify it. If this property set text will be found only in text form fields.

**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


Gets or sets the title of form field to verify it. If this property set text will be found only in text form fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


Gets or sets the type of form field to verify it. If this property set text will be found only in text form fields.

**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


Gets or sets the type of form field to verify it. If this property set text will be found only in text form fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


Specify Text Signature ID more than zero if it should be verified. This property is supported only for Pdf documents

**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


Specify Text Signature ID more than zero if it should be verified. This property is supported only for Pdf documents

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```


Overrides conversion to string.

**Returns:**
java.lang.String - 
