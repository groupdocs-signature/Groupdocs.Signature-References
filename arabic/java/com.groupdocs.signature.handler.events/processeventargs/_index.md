---
title: "ProcessEventArgs"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يوفر البيانات لأحداث مختلفة من عمليات التحقق من التوقيع والبحث."
type: docs
weight: 12
url: /ar/java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

يوفر بيانات لأحداث مختلفة لعمليات التوقيع والتحقق والبحث.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getFilePath()](#getFilePath--) | يمثل اسم ملف معالجة المستند. |
|
|  | [setFilePath(String value)](#setFilePath-java.lang.String-) | يمثل اسم ملف معالجة المستند. |
|
|  | [getStatus()](#getStatus--) | يشير إلى حالة العملية الحالية. |
|
|  | [setStatus(int value)](#setStatus-int-) | يشير إلى حالة العملية الحالية. |
|
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


يمثل اسم ملف معالجة المستند.


**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


يمثل اسم ملف معالجة المستند.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


يشير إلى حالة العملية الحالية.


**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


يشير إلى حالة العملية الحالية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

