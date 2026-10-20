---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature för Java API-referens"
description: "Anger typ av implementation för PDF-textsignatur."
type: docs
weight: 32
url: /sv/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Anger typ av implementation för PDF-textsignatur.

## Fält

| Fält | Beskrivning |
| --- | --- |
|  | [Native](#Native) | Textsignatur som inbyggt textobjekt på dokumentsida. |
|
|  | [Image](#Image) | Textsignatur som bildobjekt på dokumentsida. |
|
|  | [Annotation](#Annotation) | Textsignatur som textkommentarobjekt på PDF-sida. |
|
|  | [Sticker](#Sticker) | Textsignatur som klistermärkeobjekt på PDF-sida. |
|
|  | [FormField](#FormField) | Textsignatur som text i specificerat formulärfält. |
|
|  | [Watermark](#Watermark) | Textsignatur som vattenstämpel på dokumentsida. |
|
### Native {#Native}
```
public static final int Native
```


Textsignatur som inbyggt textobjekt på dokumentsida.


### Image {#Image}
```
public static final int Image
```


Textsignatur som bildobjekt på dokumentsida.


### Annotation {#Annotation}
```
public static final int Annotation
```


Textsignatur som textkommentarobjekt på PDF-sida.
Kommentarer är endast synliga i licensierad version.


### Sticker {#Sticker}
```
public static final int Sticker
```


Textsignatur som klistermärkeobjekt på PDF-sida.


### FormField {#FormField}
```
public static final int FormField
```


Textsignatur som text i specificerat formulärfält.
Med denna typ av implementation kan endast TextSignOptions.Text användas,
TextSignOptions.FormTextFieldType- och TextSignOptions.FormTextFieldTitle-alternativen.


### Watermark {#Watermark}
```
public static final int Watermark
```


Textsignatur som vattenstämpel på dokumentsida.


