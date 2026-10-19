---
title: "ProcessCompleteEventArgs"
second_title: "GroupDocs.Signature for Java API 参考"
description: "提供签名验证和搜索过程完成事件的数据。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

提供签名、验证和搜索过程完成事件的数据。

## 方法

| 方法 | 描述 |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | 表示过程完成的时间标记。 |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | 表示过程完成的时间标记。 |
|
|  | [getTicks()](#getTicks--) | 表示自过程开始事件以来消耗的毫秒时间。 |
|
|  | [setTicks(long value)](#setTicks-long-) | 表示自过程开始事件以来消耗的毫秒时间。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 表示已处理签名的总数量。 |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | 表示已处理签名的总数量。 |
|
|  | [getCanceled()](#getCanceled--) | 指示过程是否已取消。 |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


表示过程完成的时间标记。


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


表示过程完成的时间标记。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


表示自过程开始事件以来消耗的毫秒时间。


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


表示自过程开始事件以来消耗的毫秒时间。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


表示已处理签名的总数量。


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


表示已处理签名的总数量。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


指示过程是否已取消。


**Returns:**
boolean
