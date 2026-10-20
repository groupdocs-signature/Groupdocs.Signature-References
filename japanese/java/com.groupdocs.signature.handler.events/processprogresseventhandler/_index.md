---
title: "ProcessProgressEventHandler"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索の進捗イベントでプロセスを処理するメソッドデリゲートを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.handler.events/processprogresseventhandler/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Delegate, com.aspose.ms.System.MulticastDelegate
```
public abstract class ProcessProgressEventHandler extends System.MulticastDelegate
```

署名、検証、検索の進行イベントでプロセスを処理するメソッドデリゲートを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ProcessProgressEventHandler()](#ProcessProgressEventHandler--) |  |
## メソッド

| メソッド | 説明 |
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
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signature | [Signature](../../com.groupdocs.signature/signature) |  |
| args | [ProcessProgressEventArgs](../../com.groupdocs.signature.handler.events/processprogresseventargs) |  |

