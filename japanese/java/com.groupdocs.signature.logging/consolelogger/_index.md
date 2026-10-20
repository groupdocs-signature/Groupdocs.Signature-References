---
title: "ConsoleLogger"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ログメッセージをファイルに書き込みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.logging/consolelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class ConsoleLogger implements ILogger
```

ログメッセージをファイルに書き込みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ConsoleLogger()](#ConsoleLogger--) | コンソールにロガーを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | エラーメッセージをコンソールに書き込みます。 |
|
|  | [trace(String message)](#trace-java.lang.String-) | トレースメッセージをコンソールに書き込みます。 |
|
|  | [warning(String message)](#warning-java.lang.String-) | 警告メッセージをコンソールに書き込みます; |
警告ログメッセージは、アプリケーションフローにおける予期せぬ回復可能なイベントに関する情報を提供します。
|
### ConsoleLogger() {#ConsoleLogger--}
```
public ConsoleLogger()
```


コンソールにロガーを作成します。


### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


エラーメッセージをコンソールに書き込みます。
エラーログメッセージは、アプリケーションフローにおける回復不可能なイベントに関する情報を提供します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | message | java.lang.String | エラーメッセージ。 |
|
|  | 例外 | java.lang.Exception | 例外です。 |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


トレースメッセージをコンソールに書き込みます。
トレースログメッセージは、アプリケーションのフローに関する一般的に有用な情報を提供します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | message | java.lang.String | トレースメッセージです。 |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


警告メッセージをコンソールに書き込みます;
警告ログメッセージは、アプリケーションフローにおける予期せぬ回復可能なイベントに関する情報を提供します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | message | java.lang.String | 警告メッセージです。 |
|

