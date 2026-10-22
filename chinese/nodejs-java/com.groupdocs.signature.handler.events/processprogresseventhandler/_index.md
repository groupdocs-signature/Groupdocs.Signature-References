---
title: "ProcessProgressEventHandler"
second_title: "GroupDocs.Signature 的 Node.js 通过 Java API 参考"
description: "表示一个方法委托，用于处理签名验证和搜索的进度事件。"
type: docs
weight: 14
url: /zh/nodejs-java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

表示将在签名、验证和搜索的进度事件上处理过程的方法委托。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Signature signature, ProcessProgressEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessProgressEventArgs-) |  |
### ProcessProgressEventHandler() {#ProcessProgressEventHandler--}
```
public ProcessProgressEventHandler()
```


### invoke(Signature signature, ProcessProgressEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessProgressEventArgs-}
```
public abstract void invoke(Signature signature, ProcessProgressEventArgs args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

