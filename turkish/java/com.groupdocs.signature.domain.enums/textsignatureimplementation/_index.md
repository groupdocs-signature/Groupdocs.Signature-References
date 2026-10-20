---
title: "TextSignatureImplementation"
second_title: "Java için GroupDocs.Signature API Referansı"
description: "PDF metin imzası için uygulama türünü belirtir."
type: docs
weight: 32
url: /tr/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

PDF metin imzası için uygulama türünü belirtir.

## Alanlar

| Alan | Açıklama |
| --- | --- |
|  | [Native](#Native) | Metin İmzası, belge sayfasında yerel metin nesnesi olarak. |
|
|  | [Image](#Image) | Metin İmzası, belge sayfasında Görüntü nesnesi olarak. |
|
|  | [Annotation](#Annotation) | Metin İmzası, PDF sayfasında Metin Açıklama nesnesi olarak. |
|
|  | [Sticker](#Sticker) | Metin İmzası, PDF sayfasında Çıkartma nesnesi olarak. |
|
|  | [FormField](#FormField) | Metin İmzası, belirtilen form alanında metin olarak. |
|
|  | [Watermark](#Watermark) | Metin İmzası, belge sayfasında filigran olarak. |
|
### Native {#Native}
```
public static final int Native
```


Metin İmzası, belge sayfasında yerel metin nesnesi olarak.


### Image {#Image}
```
public static final int Image
```


Metin İmzası, belge sayfasında Görüntü nesnesi olarak.


### Annotation {#Annotation}
```
public static final int Annotation
```


Metin İmzası, PDF sayfasında Metin Açıklama nesnesi olarak.
Açıklamalar yalnızca Lisanslı sürümde görünür.


### Sticker {#Sticker}
```
public static final int Sticker
```


Metin İmzası, PDF sayfasında Çıkartma nesnesi olarak.


### FormField {#FormField}
```
public static final int FormField
```


Metin İmzası, belirtilen form alanında metin olarak.
Bu tür bir uygulama yalnızca TextSignOptions.Text kullanılabilir,
TextSignOptions.FormTextFieldType ve TextSignOptions.FormTextFieldTitle seçenekleri.


### Watermark {#Watermark}
```
public static final int Watermark
```


Metin İmzası, belge sayfasında filigran olarak.


