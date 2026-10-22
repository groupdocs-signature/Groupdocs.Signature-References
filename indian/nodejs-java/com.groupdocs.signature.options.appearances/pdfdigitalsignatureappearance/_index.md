---
title: "PdfDigitalSignatureAppearance"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "PDF दस्तावेज़ों पर डिजिटल सिग्नेचर की उपस्थिति का वर्णन करता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

PDF दस्तावेज़ों पर डिजिटल सिग्नेचर की उपस्थिति का वर्णन करता है।

--------------------

**Learn more**

 *  See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures][]
 *  See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties][]


[Advanced signing document with Digital electronic signatures]: https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/
[Advanced electronic signatures properties]: https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | डिफ़ॉल्ट मानों के साथ हस्ताक्षर रूप दिखाने वाला ऑब्जेक्ट बनाता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getContactInfoLabel()](#getContactInfoLabel--) | संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। |
| [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। |
| [getReasonLabel()](#getReasonLabel--) | कारण लेबल को प्राप्त करता है या सेट करता है। |
| [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | कारण लेबल को प्राप्त करता है या सेट करता है। |
| [getLocationLabel()](#getLocationLabel--) | स्थान लेबल को प्राप्त करता है या सेट करता है। |
| [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | स्थान लेबल को प्राप्त करता है या सेट करता है। |
| [getDigitalSignedLabel()](#getDigitalSignedLabel--) | डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। |
| [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। |
| [getDateSignedAtLabel()](#getDateSignedAtLabel--) | हस्ताक्षर की तिथि लेबल को प्राप्त करता है या सेट करता है। |
| [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | हस्ताक्षर की तिथि लेबल को प्राप्त करता है या सेट करता है। |
| [getBackground()](#getBackground--) | हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। |
| [setBackground(Color value)](#setBackground-java.awt.Color-) | हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। |
| [setBackground(String value)](#setBackground-java.lang.String-) | हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। |
| [getFontFamilyName()](#getFontFamilyName--) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट परिवार नाम को प्राप्त करता है या सेट करता है। |
| [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट परिवार नाम को प्राप्त करता है या सेट करता है। |
| [getFontSize()](#getFontSize--) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। |
| [setFontSize(double value)](#setFontSize-double-) | लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। |
| [getForeground()](#getForeground--) | हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। |
| [setForeground(Color value)](#setForeground-java.awt.Color-) | हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। |
| [setForeground(String value)](#setForeground-java.lang.String-) | हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। |
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


डिफ़ॉल्ट मानों के साथ हस्ताक्षर रूप दिखाने वाला ऑब्जेक्ट बनाता है।

### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Contact"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई संपर्क लेबल नहीं दिखेगा।

**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


संपर्क जानकारी लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Contact"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई संपर्क लेबल नहीं दिखेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


कारण लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Reason"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई कारण लेबल नहीं दिखेगा।

**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


कारण लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Reason"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई कारण लेबल नहीं दिखेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


स्थान लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Location"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई स्थान लेबल नहीं दिखेगा।

**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


स्थान लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Location"। यदि यह मान खाली है तो डिजिटल हस्ताक्षर क्षेत्र में कोई स्थान लेबल नहीं दिखेगा।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Digitally signed by"।

**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


डिजिटल साइन किया गया लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Digitally signed by"।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


हस्ताक्षर की तिथि लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Date"।

**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


हस्ताक्षर की तिथि लेबल को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान: "Date"।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान SystemColors.Windows है।

**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान SystemColors.Windows है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


हस्ताक्षर रूप दिखाने के पृष्ठभूमि रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान SystemColors.Windows है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट परिवार नाम को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान "Arial" है।

**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट परिवार नाम को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान "Arial" है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है।

**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


लेबल प्रदर्शित करने के लिए फ़ॉन्ट आकार को प्राप्त करता है या सेट करता है। डिफ़ॉल्ट मान 10 है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है।

**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


हस्ताक्षर रूप दिखाने के अग्रभूमि पाठ रंग को प्राप्त करें या सेट करें। डिफ़ॉल्ट रूप से मान Color.FromArgb(76, 100, 255) है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| मान | java.lang.String |  |

