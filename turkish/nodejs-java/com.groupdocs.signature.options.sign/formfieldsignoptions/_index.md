---
title: "FormFieldSignOptions"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "Pdf belgeleri için FormField imza seçenekleri sınıfını temsil eder."
type: docs
weight: 12
url: /tr/nodejs-java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Pdf belgeleri için FormField imza seçenekleri sınıfını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [FormFieldSignOptions()](#FormFieldSignOptions--) | PdfFormFieldSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır. |
| [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | PdfFormFieldSignOptions sınıfının yeni bir örneğini FormField imzası ile başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignature()](#getSignature--) | İmzanın FormField'ını alır veya ayarlar. |
| [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | İmzanın FormField'ını alır veya ayarlar. |
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


PdfFormFieldSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


PdfFormFieldSignOptions sınıfının yeni bir örneğini FormField imzası ile başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


İmzanın FormField'ını alır veya ayarlar.

**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


İmzanın FormField'ını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

