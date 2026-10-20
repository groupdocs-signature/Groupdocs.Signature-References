---
title: "ProcessCompleteEventArgs"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索プロセスの完了イベントに関するデータを提供します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

署名、検証、検索プロセスの完了イベントに関するデータを提供します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | プロセス完了の時刻を表します。 |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | プロセス完了の時刻を表します。 |
|
|  | [getTicks()](#getTicks--) | プロセス開始イベントから経過したミリ秒単位の時間を表します。 |
|
|  | [setTicks(long value)](#setTicks-long-) | プロセス開始イベントから経過したミリ秒単位の時間を表します。 |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 処理された署名の総数を表します。 |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | 処理された署名の総数を表します。 |
|
|  | [getCanceled()](#getCanceled--) | プロセスがキャンセルされたかどうかを示します。 |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


プロセス完了の時刻を表します。


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


プロセス完了の時刻を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


プロセス開始イベントから経過したミリ秒単位の時間を表します。


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


プロセス開始イベントから経過したミリ秒単位の時間を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


処理された署名の総数を表します。


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


処理された署名の総数を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


プロセスがキャンセルされたかどうかを示します。


**Returns:**
boolean
