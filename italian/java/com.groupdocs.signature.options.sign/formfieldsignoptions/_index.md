---
title: "FormFieldSignOptions"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Rappresenta la classe delle opzioni di firma FormField per documenti PDF."
type: docs
weight: 12
url: /it/java/com.groupdocs.signature.options.sign/formfieldsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public final class FormFieldSignOptions extends TextSignOptions
```

Rappresenta la classe delle opzioni di firma FormField per documenti PDF.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
|  | [FormFieldSignOptions()](#FormFieldSignOptions--) | Inizializza una nuova istanza della classe PdfFormFieldSignOptions con i valori predefiniti. |
|
|  | [FormFieldSignOptions(FormFieldSignature signature)](#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Inizializza una nuova istanza della classe PdfFormFieldSignOptions con la firma FormField. |
|
## Metodi

| Metodo | Descrizione |
| --- | --- |
|  | [getSignature()](#getSignature--) | Ottiene o imposta il FormField della firma. |
|
|  | [setSignature(FormFieldSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-) | Ottiene o imposta il FormField della firma. |
|
### FormFieldSignOptions() {#FormFieldSignOptions--}
```
public FormFieldSignOptions()
```


Inizializza una nuova istanza della classe PdfFormFieldSignOptions con i valori predefiniti.


### FormFieldSignOptions(FormFieldSignature signature) {#FormFieldSignOptions-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public FormFieldSignOptions(FormFieldSignature signature)
```


Inizializza una nuova istanza della classe PdfFormFieldSignOptions con la firma FormField.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| signature | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

### getSignature() {#getSignature--}
```
public final FormFieldSignature getSignature()
```


Ottiene o imposta il FormField della firma.


**Returns:**
[FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature)
### setSignature(FormFieldSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature-}
```
public final void setSignature(FormFieldSignature value)
```


Ottiene o imposta il FormField della firma.


**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [FormFieldSignature](../../com.groupdocs.signature.domain.signatures.formfield/formfieldsignature) |  |

