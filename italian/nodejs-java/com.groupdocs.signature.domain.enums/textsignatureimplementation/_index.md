---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature per Node.js tramite riferimento API Java"
description: "Specifica il tipo di implementazione per la firma di testo PDF."
type: docs
weight: 32
url: /it/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
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
| [Native](#Native) | Firma testuale come oggetto di testo nativo nella pagina del documento. |
| [Image](#Image) | Firma testuale come oggetto immagine nella pagina del documento. |
| [Annotation](#Annotation) | Firma testuale come oggetto di annotazione testuale nella pagina PDF. |
| [Sticker](#Sticker) | Firma testuale come oggetto adesivo nella pagina PDF. |
| [FormField](#FormField) | Firma testuale come testo in campo modulo specificato. |
| [Watermark](#Watermark) | Firma testuale come filigrana nella pagina del documento. |
### Native {#Native}
```
public static final int Native
```


Firma testuale come oggetto di testo nativo nella pagina del documento.

### Image {#Image}
```
public static final int Image
```


Firma testuale come oggetto immagine nella pagina del documento.

### Annotation {#Annotation}
```
public static final int Annotation
```


Firma testuale come oggetto di annotazione testuale nella pagina PDF. Le annotazioni sono visibili solo nella versione con licenza.

### Sticker {#Sticker}
```
public static final int Sticker
```


Firma testuale come oggetto adesivo nella pagina PDF.

### FormField {#FormField}
```
public static final int FormField
```


Firma testuale come testo in campo modulo specificato. Con questo tipo di implementazione possono essere utilizzate solo le opzioni TextSignOptions.Text, TextSignOptions.FormTextFieldType e TextSignOptions.FormTextFieldTitle.

### Watermark {#Watermark}
```
public static final int Watermark
```


Firma testuale come filigrana nella pagina del documento.

