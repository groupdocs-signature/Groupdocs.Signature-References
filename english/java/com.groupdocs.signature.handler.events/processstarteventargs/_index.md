---
title: ProcessStartEventArgs
second_title: GroupDocs.Editor for Java API Reference
description: Provides data for Start event of signing verification and search process
type: docs
weight: 15
url: /java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

Provides data for Start event of signing, verification and search process
## Constructors

| Constructor | Description |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getStarted()](#getStarted--) | Represents time mark of process start. |
| [setStarted(Date value)](#setStarted-java.util.Date-) | Represents time mark of process start. |
| [getTotalSignatures()](#getTotalSignatures--) | Represents total quantity of signatures to be processed. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | Represents total quantity of signatures to be processed. |
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


Represents time mark of process start.

**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


Represents time mark of process start.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Represents total quantity of signatures to be processed.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Represents total quantity of signatures to be processed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

