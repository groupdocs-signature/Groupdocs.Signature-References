---
title: TextSignatureImplementation
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Specifies type of implementation for PDF text signature.
type: docs
weight: 32
url: /nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Specifies type of implementation for PDF text signature.
## Fields

| Field | Description |
| --- | --- |
| [Native](#Native) | Text Signature as native text object on document page. |
| [Image](#Image) | Text Signature as Image object on document page. |
| [Annotation](#Annotation) | Text Signature as Text Annotation object on PDF page. |
| [Sticker](#Sticker) | Text Signature as Sticker object on PDF page. |
| [FormField](#FormField) | Text Signature as text in specified form field. |
| [Watermark](#Watermark) | Text Signature as watermark on document page. |
### Native {#Native}
```
public static final int Native
```


Text Signature as native text object on document page.

### Image {#Image}
```
public static final int Image
```


Text Signature as Image object on document page.

### Annotation {#Annotation}
```
public static final int Annotation
```


Text Signature as Text Annotation object on PDF page. Annotations are visible only for Licensed version.

### Sticker {#Sticker}
```
public static final int Sticker
```


Text Signature as Sticker object on PDF page.

### FormField {#FormField}
```
public static final int FormField
```


Text Signature as text in specified form field. With this type of implementation could be used only TextSignOptions.Text, TextSignOptions.FormTextFieldType and TextSignOptions.FormTextFieldTitle options.

### Watermark {#Watermark}
```
public static final int Watermark
```


Text Signature as watermark on document page.

