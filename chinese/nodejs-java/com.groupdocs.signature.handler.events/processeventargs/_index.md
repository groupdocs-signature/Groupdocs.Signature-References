---
title: "ProcessEventArgs"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "提供签名验证和搜索过程的各种事件的数据。"
type: docs
weight: 12
url: /zh/nodejs-java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

提供签名、验证和搜索过程的不同事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFilePath()](#getFilePath--) | 表示文档处理的文件名。 |
| [setFilePath(String value)](#setFilePath-java.lang.String-) | 表示文档处理的文件名。 |
| [getStatus()](#getStatus--) | 指示当前过程状态。 |
| [setStatus(int value)](#setStatus-int-) | 指示当前过程状态。 |
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


表示文档处理的文件名。

**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


表示文档处理的文件名。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


指示当前过程状态。

**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


指示当前过程状态。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

