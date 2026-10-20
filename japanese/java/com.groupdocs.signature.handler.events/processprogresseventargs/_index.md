---
title: "ProcessProgressEventArgs"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索プロセスの OnProgress イベントに関するデータを提供します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

署名、検証、検索プロセスの OnProgress イベントに関するデータを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getProgress()](#getProgress--) | 進捗率（パーセント）を表します。 |
|
|  | [setProgress(int value)](#setProgress-int-) | 進捗率（パーセント）を表します。 |
|
|  | [getTicks()](#getTicks--) | プロセス開始イベント以降の経過時間（ミリ秒）を表します。 |
|
|  | [setTicks(long value)](#setTicks-long-) | プロセス開始イベント以降の経過時間（ミリ秒）を表します。 |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | 処理された署名の数を表します。 |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | 処理された署名の数を表します。 |
|
|  | [getCancel()](#getCancel--) | プロセスをキャンセルすべきかどうかを示します。 |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | プロセスをキャンセルすべきかどうかを示します。 |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


進捗率（パーセント）を表します。値の範囲は 0 から 100 です。


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


進捗率（パーセント）を表します。値の範囲は 0 から 100 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


プロセス開始イベント以降の経過時間（ミリ秒）を表します。


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


プロセス開始イベント以降の経過時間（ミリ秒）を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


処理された署名の数を表します。


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


処理された署名の数を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


プロセスをキャンセルすべきかどうかを示します。


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


プロセスをキャンセルすべきかどうかを示します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

