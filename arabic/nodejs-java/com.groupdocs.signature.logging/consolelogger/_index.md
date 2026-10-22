---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يكتب رسائل السجل إلى الملف."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

يكتب رسائل السجل إلى الملف.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ConsoleLogger()](#ConsoleLogger--) | إنشاء مسجل إلى وحدة التحكم. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | يكتب رسالة خطأ إلى وحدة التحكم. |
| [trace(String message)](#trace-java.lang.String-) | يكتب رسالة تتبع إلى وحدة التحكم. |
| [warning(String message)](#warning-java.lang.String-) | يكتب رسالة تحذير إلى وحدة التحكم؛ رسائل سجل التحذير توفر معلومات حول الحدث غير المتوقع والقابل للاسترداد في تدفق التطبيق. |
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


إنشاء مسجل إلى وحدة التحكم.

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


يكتب رسالة خطأ إلى وحدة التحكم. رسائل سجل الخطأ توفر معلومات حول الأحداث غير القابلة للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة الخطأ. |
| استثناء | java.lang.Exception | الاستثناء. |

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


يكتب رسالة تتبع إلى وحدة التحكم. رسائل سجل التتبع توفر معلومات عامة مفيدة حول تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التتبع. |

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


يكتب رسالة تحذير إلى وحدة التحكم؛ رسائل سجل التحذير توفر معلومات حول الحدث غير المتوقع والقابل للاسترداد في تدفق التطبيق.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| رسالة | java.lang.String | رسالة التحذير. |

