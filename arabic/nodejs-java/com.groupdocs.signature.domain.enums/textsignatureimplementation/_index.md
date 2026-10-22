---
title: "TextSignatureImplementation"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يحدد نوع التنفيذ لتوقيع النص PDF."
type: docs
weight: 32
url: /ar/nodejs-java/com.groupdocs.signature.domain.enums/textsignatureimplementation/
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
| [Native](#Native) | توقيع نصي ككائن نصي أصلي على صفحة المستند. |
| [Image](#Image) | توقيع نصي ككائن صورة على صفحة المستند. |
| [Annotation](#Annotation) | توقيع نصي ككائن تعليقات نصية على صفحة PDF. |
| [Sticker](#Sticker) | توقيع نصي ككائن ملصق على صفحة PDF. |
| [FormField](#FormField) | توقيع نصي كنص في حقل نموذج محدد. |
| [Watermark](#Watermark) | توقيع نصي كعلامة مائية على صفحة المستند. |
### Native {#Native}
```
public static final int Native
```


توقيع نصي ككائن نصي أصلي على صفحة المستند.

### Image {#Image}
```
public static final int Image
```


توقيع نصي ككائن صورة على صفحة المستند.

### Annotation {#Annotation}
```
public static final int Annotation
```


توقيع نصي ككائن تعليقات نصية على صفحة PDF. التعليقات مرئية فقط في النسخة المرخصة.

### Sticker {#Sticker}
```
public static final int Sticker
```


توقيع نصي ككائن ملصق على صفحة PDF.

### FormField {#FormField}
```
public static final int FormField
```


توقيع نصي كنص في حقل نموذج محدد. مع هذا النوع من التنفيذ يمكن استخدام خيارات TextSignOptions.Text فقط، بالإضافة إلى خيارات TextSignOptions.FormTextFieldType و TextSignOptions.FormTextFieldTitle.

### Watermark {#Watermark}
```
public static final int Watermark
```


توقيع نصي كعلامة مائية على صفحة المستند.

