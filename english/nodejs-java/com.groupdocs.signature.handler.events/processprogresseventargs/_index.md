---
title: ProcessProgressEventArgs
second_title: GroupDocs.Signature for Node.js via Java API Reference
description: Provides data for OnProgress event of signing verification and search processes.
type: docs
weight: 13
url: /nodejs-java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

Provides data for OnProgress event of signing, verification and search processes.
## Constructors

| Constructor | Description |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getProgress()](#getProgress--) | Represents progress in percents. |
| [setProgress(int value)](#setProgress-int-) | Represents progress in percents. |
| [getTicks()](#getTicks--) | Represents time spent in milliseconds since process Start event. |
| [setTicks(long value)](#setTicks-long-) | Represents time spent in milliseconds since process Start event. |
| [getProcessedSignatures()](#getProcessedSignatures--) | Represents quantity of processed signatures. |
| [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | Represents quantity of processed signatures. |
| [getCancel()](#getCancel--) | Indicates whether process should be canceled. |
| [setCancel(boolean value)](#setCancel-boolean-) | Indicates whether process should be canceled. |
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


Represents progress in percents. Value range is from 0 to 100.

**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


Represents progress in percents. Value range is from 0 to 100.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


Represents time spent in milliseconds since process Start event.

**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


Represents time spent in milliseconds since process Start event.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


Represents quantity of processed signatures.

**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


Represents quantity of processed signatures.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


Indicates whether process should be canceled.

**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


Indicates whether process should be canceled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

