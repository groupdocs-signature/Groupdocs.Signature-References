---
title: "ProcessStartEventArgs"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索プロセスの開始イベントに関するデータを提供します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

署名、検証、検索プロセスの Start イベントに関するデータを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStarted()](#getStarted--) | プロセス開始の時刻を表します。 |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | プロセス開始の時刻を表します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理される署名の総数を表します。 |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | 処理される署名の総数を表します。 |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


プロセス開始の時刻を表します。


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


プロセス開始の時刻を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


処理される署名の総数を表します。


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


処理される署名の総数を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

