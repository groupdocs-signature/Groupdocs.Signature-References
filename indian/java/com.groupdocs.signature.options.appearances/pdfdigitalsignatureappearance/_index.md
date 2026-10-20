---
title: "PdfDigitalSignatureAppearance"
second_title: "GroupDocs.Signature for Java API संदर्भ"
description: "PDF दस्तावेज़ों पर डिजिटल सिग्नेचर की उपस्थिति का वर्णन करता है।"
type: docs
weight: 12
url: /hi/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

PDF दस्तावेज़ों पर डिजिटल सिग्नेचर की उपस्थिति का वर्णन करता है।

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | डिफ़ॉल्ट मानों के साथ सिग्नेचर अपीयरेंस ऑब्जेक्ट बनाता है। |
|
## मेथड्स

| मेथड | विवरण |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। |
|
|  | [getReasonLabel()](#getReasonLabel--) | कारण लेबल को प्राप्त करता है या सेट करता है। |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | कारण लेबल को प्राप्त करता है या सेट करता है। |
|
|  | [getLocationLabel()](#getLocationLabel--) | स्थान लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | स्थान लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | तारीख साइन किया गया लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | तारीख साइन किया गया लेबल को प्राप्त करता है या सेट करता है. |
|
|  | [getBackground()](#getBackground--) | हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट फ़ैमिली नाम को प्राप्त करता है या सेट करता है. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट फ़ैमिली नाम को प्राप्त करता है या सेट करता है. |
|
|  | [getFontSize()](#getFontSize--) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है. |
|
|  | [getForeground()](#getForeground--) | हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


डिफ़ॉल्ट मानों के साथ सिग्नेचर अपीयरेंस ऑब्जेक्ट बनाता है।


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"संपर्क\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई संपर्क लेबल नहीं दिखेगा.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"संपर्क\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई संपर्क लेबल नहीं दिखेगा.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


कारण लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"कारण\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई कारण लेबल नहीं दिखेगा.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


कारण लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"कारण\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई कारण लेबल नहीं दिखेगा.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


स्थान लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"स्थान\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई स्थान लेबल नहीं दिखेगा.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


स्थान लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"स्थान\".
यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई स्थान लेबल नहीं दिखेगा.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"डिजिटल रूप से हस्ताक्षरित द्वारा\".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"डिजिटल रूप से हस्ताक्षरित द्वारा\".


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


तारीख साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"तारीख\".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


तारीख साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: \"तारीख\".


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान SystemColors.Windows है.


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान SystemColors.Windows है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


हस्ताक्षर रूप की पृष्ठभूमि रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान SystemColors.Windows है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट फ़ैमिली नाम को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान \"Arial\" है.


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट फ़ैमिली नाम को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान \"Arial\" है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है.


**Returns:**
डबल
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | डबल |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है.


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


हस्ताक्षर रूप के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें.
डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है.


**Parameters:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

