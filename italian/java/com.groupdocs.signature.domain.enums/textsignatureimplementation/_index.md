---
title: "TextSignatureImplementation"
second_title: "Riferimento API di GroupDocs.Signature per Java"
description: "Specifica il tipo di implementazione per la firma di testo PDF."
type: docs
weight: 32
url: /it/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Specifica il tipo di implementazione per la firma di testo PDF.

## Campi

| Campo | Descrizione |
| --- | --- |
|  | [Native](#Native) | Firma testo come oggetto di testo nativo nella pagina del documento. |
|
|  | [Image](#Image) | Firma testo come oggetto immagine nella pagina del documento. |
|
|  | [Annotation](#Annotation) | Firma testo come oggetto di annotazione testo nella pagina PDF. |
|
|  | [Sticker](#Sticker) | Firma testo come oggetto adesivo nella pagina PDF. |
|
|  | [FormField](#FormField) | Firma testo come testo in campo modulo specificato. |
|
|  | [Watermark](#Watermark) | Firma testo come filigrana nella pagina del documento. |
|
### Native {#Native}
```
public static final int Native
```


Firma testo come oggetto di testo nativo nella pagina del documento.


### Image {#Image}
```
public static final int Image
```


Firma testo come oggetto immagine nella pagina del documento.


### Annotation {#Annotation}
```
public static final int Annotation
```


Firma testo come oggetto di annotazione testo nella pagina PDF.
Le annotazioni sono visibili solo per la versione con licenza.


### Sticker {#Sticker}
```
public static final int Sticker
```


Firma testo come oggetto adesivo nella pagina PDF.


### FormField {#FormField}
```
public static final int FormField
```


Firma testo come testo in campo modulo specificato.
Con questo tipo di implementazione si può usare solo TextSignOptions.Text,
opzioni TextSignOptions.FormTextFieldType e TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


Firma testo come filigrana nella pagina del documento.


