---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature لـ Node.js عبر مرجع API لجافا"
description: "يوفر البيانات لحدث البدء في عملية التحقق من التوقيع والبحث."
type: docs
weight: 15
url: /ar/nodejs-java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

يوفر بيانات لحدث Start لعملية التوقيع والتحقق والبحث.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getStarted()](#getStarted--) | يمثل علامة الوقت لبداية العملية. |
| [setStarted(Date value)](#setStarted-java.util.Date-) | يمثل علامة الوقت لبداية العملية. |
| [getTotalSignatures()](#getTotalSignatures--) | يمثل إجمالي عدد التوقيعات التي سيتم معالجتها. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | يمثل إجمالي عدد التوقيعات التي سيتم معالجتها. |
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


يمثل علامة الوقت لبداية العملية.

**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


يمثل علامة الوقت لبداية العملية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


يمثل إجمالي عدد التوقيعات التي سيتم معالجتها.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


يمثل إجمالي عدد التوقيعات التي سيتم معالجتها.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة | int |  |

