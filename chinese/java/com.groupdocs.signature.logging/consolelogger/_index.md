---
title: "ConsoleLogger"
second_title: "GroupDocs.Signature for Java API 参考"
description: "将日志消息写入文件。"
type: docs
weight: 10
url: /zh/java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

将日志消息写入文件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
|  | [ConsoleLogger()](#ConsoleLogger--) | 创建日志记录器到控制台。 |
|
## 方法

| 方法 | 描述 |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 将错误信息写入控制台。 |
|
|  | [trace(String message)](#trace-java.lang.String-) | 将跟踪信息写入控制台。 |
|
|  | [warning(String message)](#warning-java.lang.String-) | 将警告信息写入控制台； |
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


创建日志记录器到控制台。


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


将错误信息写入控制台。
错误日志消息提供有关应用程序流程中不可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 错误信息。 |
|
|  | 异常 | java.lang.Exception | 异常。 |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


将跟踪信息写入控制台。
跟踪日志消息提供有关应用程序流程的一般有用信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 跟踪信息。 |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


将警告信息写入控制台；
警告日志消息提供有关应用程序流程中意外且可恢复事件的信息。


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | message | java.lang.String | 警告信息。 |
|

