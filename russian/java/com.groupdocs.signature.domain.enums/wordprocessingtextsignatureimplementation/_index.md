---
title: "WordProcessingTextSignatureImplementation"
second_title: "GroupDocs.Signature для Java справочник API"
description: "Указывает тип реализации текстовой подписи для документов WordProcessing."
type: docs
weight: 36
url: /ru/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

Указывает тип реализации текстовой подписи для документов WordProcessing.

## Поля

| Поле | Описание |
| --- | --- |
|  | [TextStamp](#TextStamp) | Текстовая подпись как объект метки на странице Words. |
|
|  | [TextAsImage](#TextAsImage) | Текстовая подпись как объект изображения на странице Words. |
|
|  | [TextToFormField](#TextToFormField) | Текстовая подпись как текст в указанном поле формы. |
|
|  | [Watermark](#Watermark) | Текстовая подпись как водяной знак на странице Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


Текстовая подпись как объект метки на странице Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


Текстовая подпись как объект изображения на странице Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


Текстовая подпись как текст в указанном поле формы.
С этим типом реализации можно использовать только TextSignOptions.Text,
Параметры TextSignOptions.FormTextFieldTitle и TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


Текстовая подпись как водяной знак на странице Words.


