---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Anger typ av textsignaturimplementation för ordbehandlingsdokument."
type: docs
weight: 36
url: /sv/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Anger typ av textsignaturimplementation för ordbehandlingsdokument.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [TextStamp](#TextStamp) | Textsignatur som etikettobjekt på Words-sida. |
|
|  | [TextAsImage](#TextAsImage) | Textsignatur som bildobjekt på Words-sida. |
|
|  | [TextToFormField](#TextToFormField) | Textsignatur som text i specificerat formulärfält. |
|
|  | [Watermark](#Watermark) | Textsignatur som vattenstämpel på Words-sida. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Textsignatur som etikettobjekt på Words-sida.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Textsignatur som bildobjekt på Words-sida.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Textsignatur som text i specificerat formulärfält.
Med denna typ av implementation kan endast TextSignOptions.Text användas,
Alternativen TextSignOptions.FormTextFieldTitle och TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Textsignatur som vattenstämpel på Words-sida.


