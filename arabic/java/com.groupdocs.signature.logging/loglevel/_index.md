---
title: "LogLevel"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يحدد أنواع مستويات السجل المتاحة."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

يحدد أنواع مستويات السجل المتاحة.
يمكن استخدام هذا التعداد كأعلام لتعيين عدة قيم ممكنة كبتات مفعلة.
مثال: LogLevel.Error \| LogLevel.Warning أو LogLevel.Error \| LogLevel.Trace

## الحقول

| حقل | الوصف |
| --- | --- |
|  | [None](#None) | لا توجد قيود على التسجيل؛ جميع المعلومات سيتم تسجيلها من التتبع، والتحذير، إلى الأخطاء |
|
|  | [Error](#Error) | لا توجد قيود على التسجيل؛ جميع المعلومات سيتم تسجيلها من التتبع، والتحذير، إلى الأخطاء |
|
|  | [Warning](#Warning) | نفس مستوى الكل، جميع الرسائل بما في ذلك مستوى التتبع سيتم تسجيلها. |
|
|  | [Trace](#Trace) | مستوى التسجيل لتضمين الرسائل من مستوى التحذير إلى مستوى الخطأ. |
|
|  | [All](#All) | جميع أحداث مستوى السجل (خطأ، تحذير، تتبع) سيتم تضمينها في التسجيل |
|
### None {#None}
```
public static final int None
```


لا توجد قيود على التسجيل؛ جميع المعلومات سيتم تسجيلها من التتبع، والتحذير، إلى الأخطاء


### Error {#Error}
```
public static final int Error
```


لا توجد قيود على التسجيل؛ جميع المعلومات سيتم تسجيلها من التتبع، والتحذير، إلى الأخطاء


### Warning {#Warning}
```
public static final int Warning
```


نفس مستوى الكل، جميع الرسائل بما في ذلك مستوى التتبع سيتم تسجيلها.


### Trace {#Trace}
```
public static final int Trace
```


مستوى التسجيل لتضمين الرسائل من مستوى التحذير إلى مستوى الخطأ.


### All {#All}
```
public static final int All
```


جميع أحداث مستوى السجل (خطأ، تحذير، تتبع) سيتم تضمينها في التسجيل


