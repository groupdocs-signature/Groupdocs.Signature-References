---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يوفر بيانات حول حدث الاكتمال لعملية التحقق من التوقيع والبحث."
type: docs
weight: 10
url: /ar/nodejs-java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

يوفر بيانات حول حدث الاكتمال لعمليات التوقيع والتحقق والبحث.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getCompleted()](#getCompleted--) | يمثل علامة الوقت لإكمال العملية. |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | يمثل علامة الوقت لإكمال العملية. |
| [getTicks()](#getTicks--) | يمثل الوقت بالمللي ثانية المستغرق منذ حدث بدء العملية. |
| [setTicks(long value)](#setTicks-long-) | يمثل الوقت بالمللي ثانية المستغرق منذ حدث بدء العملية. |
| [getTotalSignatures()](#getTotalSignatures--) | يمثل إجمالي عدد التوقيعات المعالجة. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | يمثل إجمالي عدد التوقيعات المعالجة. |
| [getCanceled()](#getCanceled--) | يشير إلى ما إذا تم إلغاء العملية. |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


يمثل علامة الوقت لإكمال العملية.

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


يمثل علامة الوقت لإكمال العملية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


يمثل الوقت بالمللي ثانية المستغرق منذ حدث بدء العملية.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


يمثل الوقت بالمللي ثانية المستغرق منذ حدث بدء العملية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


يمثل إجمالي عدد التوقيعات المعالجة.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


يمثل إجمالي عدد التوقيعات المعالجة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


يشير إلى ما إذا تم إلغاء العملية.

**Returns:**
boolean
