---
title: "ProcessStartEventHandler"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索の開始イベントでプロセスを処理するメソッドデリゲートを表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.handler.events/processstarteventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessStartEventHandler extends System.MulticastDelegate
```

署名、検証、検索の開始イベントでプロセスを処理するメソッドデリゲートを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ProcessStartEventHandler()](#ProcessStartEventHandler--) |  |
## メソッド

| メソッド | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessStartEventArgs](../../com.groupdocs.signature.handler.events/processstarteventargs) |  |

