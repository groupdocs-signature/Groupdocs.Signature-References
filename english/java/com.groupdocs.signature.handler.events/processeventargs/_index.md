---
title: ProcessEventArgs
second_title: GroupDocs.Signature for Java API Reference
description: Provides data for different events of signature verification and search processes.
type: docs
weight: 12
url: /java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

Provides data for different events of signature, verification and search processes.
## Constructors

| Constructor | Description |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getFilePath()](#getFilePath--) | Represents document processing file name. |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | Represents document processing file name. |
| [getStatus()](#getStatus--) | Indicates current process state. |
| [setStatus(int value)](#setStatus-int-) | Indicates current process state. |
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


Represents document processing file name.

**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


Represents document processing file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


Indicates current process state.

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


Indicates current process state.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

