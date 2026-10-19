---
title: "TextSignatureImplementation"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحدد نوع التنفيذ لتوقيع النص PDF."
type: docs
weight: 32
url: /ar/java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
---
**Inheritance:**
java.lang.Object
```
public final class TextSignatureImplementation
```

يحدد نوع التنفيذ لتوقيع النص PDF.

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [Native](#Native) | توقيع النص ككائن نصي أصلي على صفحة المستند. |
|
|  | [Image](#Image) | توقيع النص ككائن صورة على صفحة المستند. |
|
|  | [Annotation](#Annotation) | توقيع النص ككائن تعليقات نصية على صفحة PDF. |
|
|  | [Sticker](#Sticker) | توقيع النص ككائن ملصق على صفحة PDF. |
|
|  | [FormField](#FormField) | توقيع النص كنص في حقل نموذج محدد. |
|
|  | [Watermark](#Watermark) | توقيع النص كعلامة مائية على صفحة المستند. |
|
### Native {#Native}
```
public static final int Native
```


توقيع النص ككائن نصي أصلي على صفحة المستند.


### Image {#Image}
```
public static final int Image
```


توقيع النص ككائن صورة على صفحة المستند.


### Annotation {#Annotation}
```
public static final int Annotation
```


توقيع النص ككائن تعليقات نصية على صفحة PDF.
التعليقات التوضيحية مرئية فقط في النسخة المرخصة.


### Sticker {#Sticker}
```
public static final int Sticker
```


توقيع النص ككائن ملصق على صفحة PDF.


### FormField {#FormField}
```
public static final int FormField
```


توقيع النص كنص في حقل نموذج محدد.
مع هذا النوع من التنفيذ يمكن استخدام فقط TextSignOptions.Text,
خيارات TextSignOptions.FormTextFieldType و TextSignOptions.FormTextFieldTitle.


### Watermark {#Watermark}
```
public static final int Watermark
```


توقيع النص كعلامة مائية على صفحة المستند.


