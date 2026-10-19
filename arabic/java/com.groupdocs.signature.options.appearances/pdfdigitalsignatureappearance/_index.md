---
title: "PdfDigitalSignatureAppearance"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يصف مظهر التوقيع الرقمي على مستندات PDF."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

يصف مظهر التوقيع الرقمي على مستندات PDF.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | ينشئ كائن مظهر التوقيع بالقيم الافتراضية. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | يحصل أو يعيّن تسمية معلومات الاتصال. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | يحصل أو يعيّن تسمية معلومات الاتصال. |
|
|  | [getReasonLabel()](#getReasonLabel--) | يحصل أو يعيّن تسمية السبب. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | يحصل أو يعيّن تسمية السبب. |
|
|  | [getLocationLabel()](#getLocationLabel--) | يحصل أو يعيّن تسمية الموقع. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | يحصل أو يعيّن تسمية الموقع. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | يحصل أو يعيّن تسمية التوقيع الرقمي. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | يحصل أو يعيّن تسمية التوقيع الرقمي. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | يحصل أو يعيّن تسمية تاريخ التوقيع. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | يحصل أو يعيّن تسمية تاريخ التوقيع. |
|
|  | [getBackground()](#getBackground--) | احصل أو عيّن لون الخلفية لمظهر التوقيع. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | احصل أو عيّن لون الخلفية لمظهر التوقيع. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | احصل أو عيّن لون الخلفية لمظهر التوقيع. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | يحصل أو يعيّن اسم عائلة الخط لعرض التسميات. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | يحصل أو يعيّن اسم عائلة الخط لعرض التسميات. |
|
|  | [getFontSize()](#getFontSize--) | يحصل أو يعيّن حجم الخط لعرض التسميات. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | يحصل أو يعيّن حجم الخط لعرض التسميات. |
|
|  | [getForeground()](#getForeground--) | احصل أو عيّن لون النص الأمامي لمظهر التوقيع. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | احصل أو عيّن لون النص الأمامي لمظهر التوقيع. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | احصل أو عيّن لون النص الأمامي لمظهر التوقيع. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


ينشئ كائن مظهر التوقيع بالقيم الافتراضية.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


يحصل أو يعيّن تسمية معلومات الاتصال. القيمة الافتراضية: "Contact".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية اتصال في منطقة التوقيع الرقمي.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


يحصل أو يعيّن تسمية معلومات الاتصال. القيمة الافتراضية: "Contact".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية اتصال في منطقة التوقيع الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


يحصل أو يعيّن تسمية السبب. القيمة الافتراضية: "Reason".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية سبب في منطقة التوقيع الرقمي.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


يحصل أو يعيّن تسمية السبب. القيمة الافتراضية: "Reason".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية سبب في منطقة التوقيع الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


يحصل أو يعيّن تسمية الموقع. القيمة الافتراضية: "Location".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية موقع في منطقة التوقيع الرقمي.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


يحصل أو يعيّن تسمية الموقع. القيمة الافتراضية: "Location".
إذا كانت هذه القيمة فارغة فلن تظهر أي تسمية موقع في منطقة التوقيع الرقمي.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


يحصل أو يعيّن تسمية التوقيع الرقمي. القيمة الافتراضية: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


يحصل أو يعيّن تسمية التوقيع الرقمي. القيمة الافتراضية: "Digitally signed by".


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


يحصل أو يعيّن تسمية تاريخ التوقيع. القيمة الافتراضية: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


يحصل أو يعيّن تسمية تاريخ التوقيع. القيمة الافتراضية: "Date".


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


احصل أو عيّن لون الخلفية لمظهر التوقيع.
افتراضيًا القيمة هي SystemColors.Windows


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


احصل أو عيّن لون الخلفية لمظهر التوقيع.
افتراضيًا القيمة هي SystemColors.Windows


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


احصل أو عيّن لون الخلفية لمظهر التوقيع.
افتراضيًا القيمة هي SystemColors.Windows


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


يحصل أو يعيّن اسم عائلة الخط لعرض التسميات. القيمة الافتراضية هي "Arial".


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


يحصل أو يعيّن اسم عائلة الخط لعرض التسميات. القيمة الافتراضية هي "Arial".


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


يحصل أو يعيّن حجم الخط لعرض التسميات. القيمة الافتراضية هي 10.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


يحصل أو يعيّن حجم الخط لعرض التسميات. القيمة الافتراضية هي 10.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


احصل أو عيّن لون النص الأمامي لمظهر التوقيع.
افتراضيًا القيمة هي Color.FromArgb(76, 100, 255)


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


احصل أو عيّن لون النص الأمامي لمظهر التوقيع.
افتراضيًا القيمة هي Color.FromArgb(76, 100, 255)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


احصل أو عيّن لون النص الأمامي لمظهر التوقيع.
افتراضيًا القيمة هي Color.FromArgb(76, 100, 255)


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

