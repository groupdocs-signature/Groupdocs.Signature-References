---
title: "ProcessCompleteEventHandler"
second_title: "GroupDocs.Signature for Java API 参考"
description: "表示一个方法委托，用于处理签名验证和搜索的完成事件。"
type: docs
weight: 11
url: /zh/java/com.groupdocs.signature.handler.events/processcompleteeventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessCompleteEventHandler extends System.MulticastDelegate
```

表示一个方法委托，用于处理签名、验证和搜索的完成事件。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ProcessCompleteEventHandler()](#ProcessCompleteEventHandler--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(Signature signature, ProcessCompleteEventArgs args)](#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessCompleteEventArgs-) |  |
### ProcessCompleteEventHandler() {#ProcessCompleteEventHandler--}
```
public ProcessCompleteEventHandler()
```


### invoke(Signature signature, ProcessCompleteEventArgs args) {#invoke-com.groupdocs.signature.Signature-com.groupdocs.signature.handler.events.ProcessCompleteEventArgs-}
```
public abstract void invoke(Signature signature, ProcessCompleteEventArgs args)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessCompleteEventArgs](../../com.groupdocs.signature.handler.events/processcompleteeventargs) |  |

