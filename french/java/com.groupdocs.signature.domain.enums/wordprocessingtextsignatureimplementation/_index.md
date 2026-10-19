---
title: "WordProcessingTextSignatureImplementation"
second_title: "Référence de l'API GroupDocs.Signature pour Java"
description: "Spécifie le type d'implémentation de signature texte pour les documents WordProcessing."
type: docs
weight: 36
url: /fr/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Spécifie le type d'implémentation de signature texte pour les documents WordProcessing.

## Champs

| Champ | Description |
| --- | --- |
|  | [TextStamp](#TextStamp) | Signature texte en tant qu'objet Label sur la page Words. |
|
|  | [TextAsImage](#TextAsImage) | Signature texte en tant qu'objet Image sur la page Words. |
|
|  | [TextToFormField](#TextToFormField) | Signature texte en tant que texte dans le champ de formulaire spécifié. |
|
|  | [Watermark](#Watermark) | Signature texte en tant que filigrane sur la page Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Signature texte en tant qu'objet Label sur la page Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Signature texte en tant qu'objet Image sur la page Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Signature texte en tant que texte dans le champ de formulaire spécifié.
Avec ce type d'implémentation, seul TextSignOptions.Text peut être utilisé,
Options TextSignOptions.FormTextFieldTitle et TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Signature texte en tant que filigrane sur la page Words.


