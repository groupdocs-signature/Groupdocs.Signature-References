---
title: ProcessCompleteEventArgs
second_title: GroupDocs.Signature for Java API Reference
description: Provides data on complete event of signing verification and search processes.
type: docs
weight: 10
url: /java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

Provides data on complete event of signing, verification and search processes.
## Methods

| Method | Description |
| --- | --- |
| [getCompleted()](#getCompleted--) | Represents time mark of process completion. |
| [setCompleted(Date value)](#setCompleted-java.util.Date-) | Represents time mark of process completion. |
| [getTicks()](#getTicks--) | Represents time in milliseconds spent since process Start event. |
| [setTicks(long value)](#setTicks-long-) | Represents time in milliseconds spent since process Start event. |
| [getTotalSignatures()](#getTotalSignatures--) | Represents total quantity of processed signatures. |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | Represents total quantity of processed signatures. |
| [getCanceled()](#getCanceled--) | Indicates whether process was canceled. |
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


Represents time mark of process completion.

**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


Represents time mark of process completion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Represents time in milliseconds spent since process Start event.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Represents time in milliseconds spent since process Start event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


Represents total quantity of processed signatures.

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


Represents total quantity of processed signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


Indicates whether process was canceled.

**Returns:**
boolean
