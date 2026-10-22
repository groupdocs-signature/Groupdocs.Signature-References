---
title: "FormFieldSignOptions"
second_title: "Node.js के लिए GroupDocs.Signature जावा API रेफ़रेंस के माध्यम से"
description: "Pdf दस्तावेज़ों के लिए FormField हस्ताक्षर विकल्पों की क्लास का प्रतिनिधित्व करता है।"
type: docs
weight: 12
url: /hi/nodejs-java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Pdf दस्तावेज़ों के लिए FormField हस्ताक्षर विकल्पों की क्लास का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर्स

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [FormFieldSignOptions()](#FormFieldSignOptions--) | PdfFormFieldSignOptions क्लास का नया इंस्टेंस डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है। |
| [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | PdfFormFieldSignOptions क्लास का नया इंस्टेंस FormField सिग्नेचर के साथ इनिशियलाइज़ करता है। |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getSignature()](#getSignature--) | सिग्नेचर के FormField को प्राप्त करता है या सेट करता है। |
| [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | सिग्नेचर के FormField को प्राप्त करता है या सेट करता है। |
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


PdfFormFieldSignOptions क्लास का नया इंस्टेंस डिफ़ॉल्ट मानों के साथ इनिशियलाइज़ करता है।

### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


PdfFormFieldSignOptions क्लास का नया इंस्टेंस FormField सिग्नेचर के साथ इनिशियलाइज़ करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


सिग्नेचर के FormField को प्राप्त करता है या सेट करता है।

**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


सिग्नेचर के FormField को प्राप्त करता है या सेट करता है।

**Parameters:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

