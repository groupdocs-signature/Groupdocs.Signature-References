---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature pour Node.js via la référence de l'API Java"
description: "Spécifie le type d’implémentation de signature texte pour les documents WordProcessing."
type: docs
weight: 36
url: /fr/nodejs-java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Spécifie le type d’implémentation de signature texte pour les documents WordProcessing.
## Champs

| Champ | Description |
| --- | --- |
| [TextStamp](#TextStamp) | Signature texte en tant qu'objet Label sur la page Words. |
| [TextAsImage](#TextAsImage) | Signature texte en tant qu'objet Image sur la page Words. |
| [TextToFormField](#TextToFormField) | Signature texte en tant que texte dans le champ de formulaire spécifié. |
| [Watermark](#Watermark) | Signature texte en tant que filigrane sur la page Words. |
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


Signature texte en tant que texte dans le champ de formulaire spécifié. Avec ce type d'implémentation, seules les options TextSignOptions.Text, TextSignOptions.FormTextFieldTitle et TextSignOptions.FormTextFieldType pourraient être utilisées.

### Watermark {#Watermark}
```
public static final int Watermark
```


Signature texte en tant que filigrane sur la page Words.

