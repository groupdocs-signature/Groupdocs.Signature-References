---
title: "WordProcessingTextSignatureImplementation"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Specifica il tipo di implementazione della firma di testo per i documenti WordProcessing."
type: docs
weight: 36
url: /it/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Specifica il tipo di implementazione della firma di testo per i documenti WordProcessing.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [TextStamp](#TextStamp) | Firma di testo come oggetto Etichetta nella pagina Words. |
|
|  | [TextAsImage](#TextAsImage) | Firma di testo come oggetto Immagine nella pagina Words. |
|
|  | [TextToFormField](#TextToFormField) | Firma testo come testo in campo modulo specificato. |
|
|  | [Watermark](#Watermark) | Firma di testo come filigrana nella pagina Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Firma di testo come oggetto Etichetta nella pagina Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Firma di testo come oggetto Immagine nella pagina Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Firma testo come testo in campo modulo specificato.
Con questo tipo di implementazione si può usare solo TextSignOptions.Text,
Opzioni TextSignOptions.FormTextFieldTitle e TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Firma di testo come filigrana nella pagina Words.


