---
title: "ProcessEventArgs"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名検証および検索プロセスのさまざまなイベントに関するデータを提供します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

署名、検証、検索プロセスのさまざまなイベントに関するデータを提供します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFilePath()](#getFilePath--) | ドキュメント処理のファイル名を表します。 |
|
|  | [setFilePath(String value)](#setFilePath-java.lang.String-) | ドキュメント処理のファイル名を表します。 |
|
|  | [getStatus()](#getStatus--) | 現在のプロセス状態を示します。 |
|
|  | [setStatus(int value)](#setStatus-int-) | 現在のプロセス状態を示します。 |
|
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


ドキュメント処理のファイル名を表します。


**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


ドキュメント処理のファイル名を表します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


現在のプロセス状態を示します。


**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


現在のプロセス状態を示します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

