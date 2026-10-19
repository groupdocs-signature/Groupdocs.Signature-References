---
title: "ProcessProgressEventArgs"
second_title: "مرجع API لـ GroupDocs.Signature للغة Java"
description: "يوفر البيانات لحدث OnProgress لعمليات التحقق من التوقيع والبحث."
type: docs
weight: 13
url: /ar/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

يوفر بيانات لحدث OnProgress لعمليات التوقيع والتحقق والبحث.

## البناؤون

| منشئ | الوصف |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
|  | [getProgress()](#getProgress--) | يمثل التقدم بالنسبة المئوية. |
|
|  | [setProgress(int value)](#setProgress-int-) | يمثل التقدم بالنسبة المئوية. |
|
|  | [getTicks()](#getTicks--) | يمثل الوقت المستغرق بالمللي ثانية منذ حدث بدء العملية. |
|
|  | [setTicks(long value)](#setTicks-long-) | يمثل الوقت المستغرق بالمللي ثانية منذ حدث بدء العملية. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | يمثل عدد التوقيعات المعالجة. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | يمثل عدد التوقيعات المعالجة. |
|
|  | [getCancel()](#getCancel--) | يشير إلى ما إذا كان يجب إلغاء العملية. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | يشير إلى ما إذا كان يجب إلغاء العملية. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


يمثل التقدم بالنسبة المئوية. نطاق القيمة من 0 إلى 100.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


يمثل التقدم بالنسبة المئوية. نطاق القيمة من 0 إلى 100.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


يمثل الوقت المستغرق بالمللي ثانية منذ حدث بدء العملية.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


يمثل الوقت المستغرق بالمللي ثانية منذ حدث بدء العملية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


يمثل عدد التوقيعات المعالجة.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


يمثل عدد التوقيعات المعالجة.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


يشير إلى ما إذا كان يجب إلغاء العملية.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


يشير إلى ما إذا كان يجب إلغاء العملية.


**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | boolean |  |

