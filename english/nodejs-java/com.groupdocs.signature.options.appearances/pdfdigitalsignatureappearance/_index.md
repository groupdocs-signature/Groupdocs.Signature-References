---
title: PdfDigitalSignatureAppearance
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Describes appearance of Digital Signature are on PDF documents.
type: docs
weight: 12
url: /nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

Describes appearance of Digital Signature are on PDF documents.

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## Constructors

| Constructor | Description |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | Creates signature appearance object with default values. |
## Methods

| Method | Description |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | Gets or sets contact info label. |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | Gets or sets contact info label. |
| [getReasonLabel()](#getReasonLabel--) | Gets or sets reason label. |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | Gets or sets reason label. |
| [getLocationLabel()](#getLocationLabel--) | Gets or sets location label. |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | Gets or sets location label. |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | Gets or sets digital signed label. |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | Gets or sets digital signed label. |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | Gets or sets date signed label. |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | Gets or sets date signed label. |
| [getBackground()](#getBackground--) | Get or set background color of signature appearance. |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | Get or set background color of signature appearance. |
| [setBackground(String value)](#setBackground-java.lang.String-) | Get or set background color of signature appearance. |
| [getFontFamilyName()](#getFontFamilyName--) | Gets or sets the Font family name to display the labels. |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | Gets or sets the Font family name to display the labels. |
| [getFontSize()](#getFontSize--) | Gets or sets the Font size to display the labels. |
| [setFontSize(double value)](#setFontSize-double-) | Gets or sets the Font size to display the labels. |
| [getForeground()](#getForeground--) | Get or set foreground text color of signature appearance. |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | Get or set foreground text color of signature appearance. |
| [setForeground(String value)](#setForeground-java.lang.String-) | Get or set foreground text color of signature appearance. |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


Creates signature appearance object with default values.

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


Gets or sets contact info label. Default value: "Contact". if this value is empty then no contact label will appear on digital signature area.

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


Gets or sets contact info label. Default value: "Contact". if this value is empty then no contact label will appear on digital signature area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


Gets or sets reason label. Default value: "Reason". if this value is empty then no reason label will appear on digital signature area.

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


Gets or sets reason label. Default value: "Reason". if this value is empty then no reason label will appear on digital signature area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


Gets or sets location label. Default value: "Location". if this value is empty then no location label will appear on digital signature area.

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


Gets or sets location label. Default value: "Location". if this value is empty then no location label will appear on digital signature area.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


Gets or sets digital signed label. Default value: "Digitally signed by".

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


Gets or sets digital signed label. Default value: "Digitally signed by".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


Gets or sets date signed label. Default value: "Date".

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


Gets or sets date signed label. Default value: "Date".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


Get or set background color of signature appearance. By default the value is SystemColors.Windows

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


Get or set background color of signature appearance. By default the value is SystemColors.Windows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


Get or set background color of signature appearance. By default the value is SystemColors.Windows

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


Gets or sets the Font family name to display the labels. Default value is "Arial".

**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


Gets or sets the Font family name to display the labels. Default value is "Arial".

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


Gets or sets the Font size to display the labels. Default value is 10.

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


Gets or sets the Font size to display the labels. Default value is 10.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


Get or set foreground text color of signature appearance. By default the value is Color.FromArgb(76, 100, 255)

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


Get or set foreground text color of signature appearance. By default the value is Color.FromArgb(76, 100, 255)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


Get or set foreground text color of signature appearance. By default the value is Color.FromArgb(76, 100, 255)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

