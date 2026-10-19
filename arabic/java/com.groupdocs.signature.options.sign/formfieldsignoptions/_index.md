---
title: "FormFieldSignOptions"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يمثل فئة خيارات توقيع حقل النموذج للمستندات PDF."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

يمثل فئة خيارات توقيع حقل النموذج للمستندات PDF.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | ينشئ مثيلًا جديدًا من الفئة PdfFormFieldSignOptions بالقيم الافتراضية. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | ينشئ مثيلًا جديدًا من الفئة PdfFormFieldSignOptions بتوقيع FormField. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getSignature()](#getSignature--) | يحصل أو يضبط FormField للتوقيع. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | يحصل أو يضبط FormField للتوقيع. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


ينشئ مثيلًا جديدًا من الفئة PdfFormFieldSignOptions بالقيم الافتراضية.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


ينشئ مثيلًا جديدًا من الفئة PdfFormFieldSignOptions بتوقيع FormField.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


يحصل أو يضبط FormField للتوقيع.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


يحصل أو يضبط FormField للتوقيع.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

