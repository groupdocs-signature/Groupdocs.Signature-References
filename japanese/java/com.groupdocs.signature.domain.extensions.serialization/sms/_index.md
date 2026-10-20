---
title: "SMS"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "SMS 短信サービスの詳細を表します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

SMS 短信サービスの詳細を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SMS()](#SMS--) | デフォルト値で VCard インスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getNumber()](#getNumber--) | SMS 受信者の電話番号を取得または設定します。 |
|
|  | [setNumber(String value)](#setNumber-java.lang.String-) | SMS 受信者の電話番号を取得または設定します。 |
|
|  | [getMessage()](#getMessage--) | SMS メッセージの内容を取得または設定します。 |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | SMS メッセージの内容を取得または設定します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | SMS プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### SMS() {#SMS--}
```
public SMS()
```


デフォルト値で VCard インスタンスを作成します。


### getNumber() {#getNumber--}
```
public final String getNumber()
```


SMS 受信者の電話番号を取得または設定します。


**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


SMS 受信者の電話番号を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


SMS メッセージの内容を取得または設定します。


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


SMS メッセージの内容を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


SMS プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 比較対象となる SMS オブジェクト。 |
|

**Returns:**
boolean - 渡された SMS オブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - VCard のハッシュコード

