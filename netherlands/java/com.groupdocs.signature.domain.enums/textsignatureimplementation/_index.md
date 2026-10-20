---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature voor Java API-referentie"
description: "Specificeert het type implementatie voor PDF-teksthandtekening."
type: docs
weight: 32
url: /nl/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Specificeert het type implementatie voor PDF-teksthandtekening.

## Velden

| Veld | Beschrijving |
| --- | --- |
|  | [Native](#Native) | Teksthandtekening als native tekstobject op documentpagina. |
|
|  | [Image](#Image) | Teksthandtekening als afbeeldingobject op documentpagina. |
|
|  | [Annotation](#Annotation) | Teksthandtekening als tekstannotatie-object op PDF-pagina. |
|
|  | [Sticker](#Sticker) | Teksthandtekening als stickerobject op PDF-pagina. |
|
|  | [FormField](#FormField) | Teksthandtekening als tekst in opgegeven formulierveld. |
|
|  | [Watermark](#Watermark) | Teksthandtekening als watermerk op documentpagina. |
|
### Native {#Native}
```
public static final int Native
```


Teksthandtekening als native tekstobject op documentpagina.


### Image {#Image}
```
public static final int Image
```


Teksthandtekening als afbeeldingobject op documentpagina.


### Annotation {#Annotation}
```
public static final int Annotation
```


Teksthandtekening als tekstannotatie-object op PDF-pagina.
Annotaties zijn alleen zichtbaar voor gelicentieerde versie.


### Sticker {#Sticker}
```
public static final int Sticker
```


Teksthandtekening als stickerobject op PDF-pagina.


### FormField {#FormField}
```
public static final int FormField
```


Teksthandtekening als tekst in opgegeven formulierveld.
Met dit type implementatie kan alleen TextSignOptions.Text worden gebruikt,
TextSignOptions.FormTextFieldType- en TextSignOptions.FormTextFieldTitle-opties.


### Watermark {#Watermark}
```
public static final int Watermark
```


Teksthandtekening als watermerk op documentpagina.


