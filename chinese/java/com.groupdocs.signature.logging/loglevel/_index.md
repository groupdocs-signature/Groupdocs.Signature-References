---
title: "LogLevel"
second_title: "GroupDocs.Signature for Java API 参考"
description: "指定可用的日志级别类型。"
type: docs
weight: 12
url: /zh/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

指定可用的日志级别类型。
此枚举可用作标志，以将多个可能的值设置为启用位
示例：LogLevel.Error \| LogLevel.Warning or LogLevel.Error \| LogLevel.Trace

## 字段

| 字段 | 描述 |
| --- | --- |
|  | [None](#None) | 没有日志限制，所有信息将从跟踪、警告到错误全部记录 |
|
|  | [Error](#Error) | 没有日志限制，所有信息将从跟踪、警告到错误全部记录 |
|
|  | [Warning](#Warning) | 与 All 级别相同，所有消息包括跟踪级别都将被记录 |
|
|  | [Trace](#Trace) | 日志级别包括从警告到错误级别的消息 |
|
|  | [All](#All) | 所有日志级别事件（错误、警告、跟踪）都将包含在日志中 |
|
### None {#None}
```
public static final int None
```


没有日志限制，所有信息将从跟踪、警告到错误全部记录


### Error {#Error}
```
public static final int Error
```


没有日志限制，所有信息将从跟踪、警告到错误全部记录


### Warning {#Warning}
```
public static final int Warning
```


与 All 级别相同，所有消息包括跟踪级别都将被记录


### Trace {#Trace}
```
public static final int Trace
```


日志级别包括从警告到错误级别的消息


### All {#All}
```
public static final int All
```


所有日志级别事件（错误、警告、跟踪）都将包含在日志中


