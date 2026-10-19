---
title: "TextSignatureImplementation"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Spécifie le type d'implémentation pour la signature texte PDF."
type: docs
weight: 32
url: /fr/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Spécifie le type d'implémentation pour la signature texte PDF.

## Champs

| Champ | Description |
| --- | --- |
|  | [Native](#Native) | Signature texte en tant qu'objet texte natif sur la page du document. |
|
|  | [Image](#Image) | Signature texte en tant qu'objet image sur la page du document. |
|
|  | [Annotation](#Annotation) | Signature texte en tant qu'objet annotation texte sur la page PDF. |
|
|  | [Sticker](#Sticker) | Signature texte en tant qu'objet autocollant sur la page PDF. |
|
|  | [FormField](#FormField) | Signature texte en tant que texte dans le champ de formulaire spécifié. |
|
|  | [Watermark](#Watermark) | Signature texte en tant que filigrane sur la page du document. |
|
### Native {#Native}
```
public static final int Native
```


Signature texte en tant qu'objet texte natif sur la page du document.


### Image {#Image}
```
public static final int Image
```


Signature texte en tant qu'objet image sur la page du document.


### Annotation {#Annotation}
```
public static final int Annotation
```


Signature texte en tant qu'objet annotation texte sur la page PDF.
Les annotations sont visibles uniquement pour la version sous licence.


### Sticker {#Sticker}
```
public static final int Sticker
```


Signature texte en tant qu'objet autocollant sur la page PDF.


### FormField {#FormField}
```
public static final int FormField
```


Signature texte en tant que texte dans le champ de formulaire spécifié.
Avec ce type d'implémentation, seul TextSignOptions.Text peut être utilisé,
options TextSignOptions.FormTextFieldType et TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


Signature texte en tant que filigrane sur la page du document.


