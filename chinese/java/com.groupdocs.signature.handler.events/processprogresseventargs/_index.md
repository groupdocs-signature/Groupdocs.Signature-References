---
title: "ProcessProgressEventArgs"
second_title: "GroupDocs.Signature for Java API 参考"
description: "提供签名验证和搜索过程的 OnProgress 事件的数据。"
type: docs
weight: 13
url: /zh/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

提供签名、验证和搜索过程的 OnProgress 事件的数据。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getProgress()](#getProgress--) | 表示以百分比计的进度。 |
|
|  | [setProgress(int value)](#setProgress-int-) | 表示以百分比计的进度。 |
|
|  | [getTicks()](#getTicks--) | 表示自过程 Start 事件以来耗费的毫秒时间。 |
|
|  | [setTicks(long value)](#setTicks-long-) | 表示自过程 Start 事件以来耗费的毫秒时间。 |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | 表示已处理的签名数量。 |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | 表示已处理的签名数量。 |
|
|  | [getCancel()](#getCancel--) | 指示是否应取消过程。 |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | 指示是否应取消过程。 |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


表示以百分比形式的进度。取值范围为 0 到 100。


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


表示以百分比形式的进度。取值范围为 0 到 100。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


表示自过程 Start 事件以来耗费的毫秒时间。


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


表示自过程 Start 事件以来耗费的毫秒时间。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


表示已处理的签名数量。


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


表示已处理的签名数量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


指示是否应取消过程。


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


指示是否应取消过程。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

