---
title: FormFieldSignOptions
second_title: GroupDocs.Editor for Java API Reference
description: Represents class of the FormField signature options for Pdf documents.
type: docs
weight: 12
url: /java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Represents class of the FormField signature options for Pdf documents.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormFieldSignOptions()](#FormFieldSignOptions--) | Initializes a new instance of the PdfFormFieldSignOptions class with default values. |
| [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Initializes a new instance of the PdfFormFieldSignOptions class with FormField signature. |
## Methods

| Method | Description |
| --- | --- |
| [getSignature()](#getSignature--) | Gets or sets the FormField of signature. |
| [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Gets or sets the FormField of signature. |
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


Initializes a new instance of the PdfFormFieldSignOptions class with default values.

### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


Initializes a new instance of the PdfFormFieldSignOptions class with FormField signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


Gets or sets the FormField of signature.

**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


Gets or sets the FormField of signature.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

