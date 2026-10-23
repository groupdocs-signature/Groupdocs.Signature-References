---
title: "TextSignatureImplementation"
second_title: "Java API Referansı aracılığıyla Node.js için GroupDocs.Signature"
description: "PDF metin imzası için uygulama tipini belirtir."
type: docs
weight: 32
url: /tr/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

PDF metin imzası için uygulama tipini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Native](#Native) | Text Signature belge sayfasında yerel metin nesnesi olarak. |
| [Image](#Image) | Text Signature belge sayfasında Görüntü nesnesi olarak. |
| [Annotation](#Annotation) | Text Signature PDF sayfasında Metin Açıklama nesnesi olarak. |
| [Sticker](#Sticker) | Text Signature PDF sayfasında Sticker nesnesi olarak. |
| [FormField](#FormField) | Text Signature belirtilen form alanında metin olarak. |
| [Watermark](#Watermark) | Text Signature belge sayfasında filigran olarak. |
### Native {#Native}
```
public static final int Native
```


Text Signature belge sayfasında yerel metin nesnesi olarak.

### Image {#Image}
```
public static final int Image
```


Text Signature belge sayfasında Görüntü nesnesi olarak.

### Annotation {#Annotation}
```
public static final int Annotation
```


Text Signature PDF sayfasında Metin Açıklama nesnesi olarak. Açıklamalar yalnızca Lisanslı sürümde görünür.

### Sticker {#Sticker}
```
public static final int Sticker
```


Text Signature PDF sayfasında Sticker nesnesi olarak.

### FormField {#FormField}
```
public static final int FormField
```


Text Signature belirtilen form alanında metin olarak. Bu tür bir uygulama yalnızca TextSignOptions.Text, TextSignOptions.FormTextFieldType ve TextSignOptions.FormTextFieldTitle seçenekleriyle kullanılabilir.

### Watermark {#Watermark}
```
public static final int Watermark
```


Text Signature belge sayfasında filigran olarak.

