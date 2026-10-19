---
title: "WordProcessingTextSignatureImplementation"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحدد نوع تنفيذ توقيع النص لمستندات معالجة الكلمات."
type: docs
weight: 36
url: /ar/java/com.groupdocs.signature.domain.enums/wordprocessingtextsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class WordProcessingTextSignatureImplementation
```

يحدد نوع تنفيذ توقيع النص لمستندات معالجة الكلمات.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [TextStamp](#TextStamp) | توقيع نصي ككائن تسمية على صفحة Words. |
|
|  | [TextAsImage](#TextAsImage) | توقيع نصي ككائن صورة على صفحة Words. |
|
|  | [TextToFormField](#TextToFormField) | توقيع النص كنص في حقل نموذج محدد. |
|
|  | [Watermark](#Watermark) | توقيع نصي كعلامة مائية على صفحة Words. |
|
### TextStamp {#TextStamp}
```
public static final int TextStamp
```


توقيع نصي ككائن تسمية على صفحة Words.


### TextAsImage {#TextAsImage}
```
public static final int TextAsImage
```


توقيع نصي ككائن صورة على صفحة Words.


### TextToFormField {#TextToFormField}
```
public static final int TextToFormField
```


توقيع النص كنص في حقل نموذج محدد.
مع هذا النوع من التنفيذ يمكن استخدام فقط TextSignOptions.Text,
خيارات TextSignOptions.FormTextFieldTitle و TextSignOptions.FormTextFieldType.


### Watermark {#Watermark}
```
public static final int Watermark
```


توقيع نصي كعلامة مائية على صفحة Words.


