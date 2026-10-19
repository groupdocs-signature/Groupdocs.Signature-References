---
title: "FormFieldSignOptions"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Représente la classe des options de signature de champ de formulaire pour les documents PDF."
type: docs
weight: 12
url: /fr/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Représente la classe des options de signature de champ de formulaire pour les documents PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec les valeurs par défaut. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec une signature FormField. |
|
## Méthodes

| Méthode | Description |
| --- | --- |
|  | [getSignature()](#getSignature--) | Obtient ou définit le FormField de la signature. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Obtient ou définit le FormField de la signature. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec les valeurs par défaut.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


Initialise une nouvelle instance de la classe PdfFormFieldSignOptions avec une signature FormField.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


Obtient ou définit le FormField de la signature.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


Obtient ou définit le FormField de la signature.


**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

