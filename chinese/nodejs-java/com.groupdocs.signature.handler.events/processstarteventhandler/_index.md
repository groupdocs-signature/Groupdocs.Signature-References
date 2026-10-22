---
title: "ProcessStartEventHandler"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示一个方法委托，用于处理签名验证和搜索的启动事件。"
type: docs
weight: 16
url: /zh/nodejs-java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

表示将在签名、验证和搜索的开始事件上处理过程的方法委托。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Signature signature, ProcessStartEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-) |  |
### ProcessStartEventHandler() {#ProcessStartEventHandler--}
```
public ProcessStartEventHandler()
```


### invoke(Signature signature, ProcessStartEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessStartEventArgs-}
```
public abstract void invoke(Signature signature, ProcessStartEventArgs args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

