---
title: "LogLevel"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "SignatureSettingsで設定されたロガーに渡されるメッセージの種類を指定します。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

ロガーに設定されたものへ渡されるメッセージの種類を指定します。
SignatureSettings
.
これらの値はフラグであり、例えば組み合わせることができます。
LogLevel.Error \| LogLevel.Warning
.

## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [None](#None) | 何も記録されません。 |
|
|  | [Error](#Error) | エラー: 操作が失敗しました。 |
|
|  | [Warning](#Warning) | 警告: 操作は成功しましたが、結果が期待通りでない可能性があります。 |
|
|  | [Trace](#Trace) | トレース: 操作のステップ、開始と終了など。 |
|
|  | [All](#All) | エラー、警告、トレース。 |
|
### None {#None}
```
public static final int None
```


何も記録されません。


### Error {#Error}
```
public static final int Error
```


エラー: 操作が失敗しました。


### Warning {#Warning}
```
public static final int Warning
```


警告: 操作は成功しましたが、結果が期待通りでない可能性があります。


### Trace {#Trace}
```
public static final int Trace
```


トレース: 操作のステップ、開始と終了など。


### All {#All}
```
public static final int All
```


エラー、警告、トレース。これはデフォルトです。


