---
title: "FormFieldSignOptions"
second_title: "Referencia de API de GroupDocs.Signature para Java"
description: "Representa la clase de las opciones de firma FormField para documentos Pdf."
type: docs
weight: 12
url: /es/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Representa la clase de las opciones de firma FormField para documentos Pdf.

## Constructores

| Constructor | Descripción |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con valores predeterminados. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con la firma FormField. |
|
## Métodos

| Método | Descripción |
| --- | --- |
|  | [getSignature()](#getSignature--) | Obtiene o establece el FormField de la firma. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Obtiene o establece el FormField de la firma. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con valores predeterminados.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


Inicializa una nueva instancia de la clase PdfFormFieldSignOptions con la firma FormField.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


Obtiene o establece el FormField de la firma.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


Obtiene o establece el FormField de la firma.


**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

