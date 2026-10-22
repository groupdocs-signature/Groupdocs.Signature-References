---
title: "ProcessStartEventArgs"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "提供签名验证和搜索过程的 Start 事件的数据。"
type: docs
weight: 15
url: /zh/nodejs-java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

提供签名、验证和搜索过程的 Start 事件的数据
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStarted()](#getStarted--) | 表示过程开始的时间标记。 |
| [setStarted(Date value)](#setStarted-java.util.Date-) | 表示过程开始的时间标记。 |
| [getTotalSignatures()](#getTotalSignatures--) | 表示要处理的签名的总数量。 |
| [setTotalSignatures(int value)](#setTotalSignatures-int-) | 表示要处理的签名的总数量。 |
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


表示过程开始的时间标记。

**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


表示过程开始的时间标记。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


表示要处理的签名的总数量。

**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


表示要处理的签名的总数量。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

