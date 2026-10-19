---
title: "FileLogger"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يكتب رسائل السجل إلى الملف."
type: docs
weight: 11
url: /ar/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

يكتب رسائل السجل إلى الملف.

## البناؤون

| منشئ | الوصف |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | إنشاء مسجل إلى ملف. |
|
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | يكتب رسالة خطأ إلى وحدة التحكم. |
|
|  | [trace(String message)](#trace-java.lang.String-) | يكتب رسالة تتبع إلى وحدة التحكم. |
|
|  | [warning(String message)](#warning-java.lang.String-) | يكتب رسالة تحذير إلى وحدة التحكم؛ |
توفر رسائل سجل التحذير معلومات حول الحدث غير المتوقع والقابل للاسترداد في تدفق التطبيق.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


إنشاء مسجل إلى ملف.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | fileName | java.lang.String | اسم الملف الكامل مع المسار |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


يكتب رسالة خطأ إلى وحدة التحكم.
توفر رسائل سجل الخطأ معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | رسالة الخطأ. |
|
|  | استثناء | java.lang.Exception | الاستثناء. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


يكتب رسالة تتبع إلى وحدة التحكم.
توفر رسائل سجل التتبع معلومات عامة مفيدة حول تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | رسالة التتبع. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


يكتب رسالة تحذير إلى وحدة التحكم؛
توفر رسائل سجل التحذير معلومات حول الحدث غير المتوقع والقابل للاسترداد في تدفق التطبيق.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
|  | message | java.lang.String | رسالة التحذير. |
|

