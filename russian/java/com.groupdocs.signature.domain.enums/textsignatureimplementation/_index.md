---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Указывает тип реализации для текстовой подписи PDF."
type: docs
weight: 32
url: /ru/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

Указывает тип реализации для текстовой подписи PDF.

## Поля

| Поле | Описание |
| --- | --- |
|  | [Native](#Native) | Текстовая подпись как нативный текстовый объект на странице документа. |
|
|  | [Image](#Image) | Текстовая подпись как объект изображения на странице документа. |
|
|  | [Annotation](#Annotation) | Текстовая подпись как объект текстовой аннотации на странице PDF. |
|
|  | [Sticker](#Sticker) | Текстовая подпись как объект стикера на странице PDF. |
|
|  | [FormField](#FormField) | Текстовая подпись как текст в указанном поле формы. |
|
|  | [Watermark](#Watermark) | Текстовая подпись как водяной знак на странице документа. |
|
### Native {#Native}
```
public static final int Native
```


Текстовая подпись как нативный текстовый объект на странице документа.


### Image {#Image}
```
public static final int Image
```


Текстовая подпись как объект изображения на странице документа.


### Annotation {#Annotation}
```
public static final int Annotation
```


Текстовая подпись как объект текстовой аннотации на странице PDF.
Аннотации видимы только в лицензированной версии.


### Sticker {#Sticker}
```
public static final int Sticker
```


Текстовая подпись как объект стикера на странице PDF.


### FormField {#FormField}
```
public static final int FormField
```


Текстовая подпись как текст в указанном поле формы.
С этим типом реализации можно использовать только TextSignOptions.Text,
Опции TextSignOptions.FormTextFieldType и TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


Текстовая подпись как водяной знак на странице документа.


