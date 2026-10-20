---
title: "メール"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "QRコード用のメール形式を表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/email/
---
**Inheritance:**
java.lang.Object
```
public class Email
```

QRコード用のメール形式を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Email()](#Email--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAddress()](#getAddress--) | メールアドレスを取得または設定します。 |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | メールアドレスを取得または設定します。 |
|
|  | [getSubject()](#getSubject--) | メールの件名を取得または設定します。 |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | メールの件名を取得または設定します。 |
|
|  | [getBody()](#getBody--) | メールメッセージの本文を取得または設定します。 |
|
|  | [setBody(String value)](#setBody-java.lang.String-) | メールメッセージの本文を取得または設定します。 |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Email プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### Email() {#Email--}
```
public Email()
```


### getAddress() {#getAddress--}
```
public final String getAddress()
```


メールアドレスを取得または設定します。


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


メールアドレスを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


メールの件名を取得または設定します。


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


メールの件名を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getBody() {#getBody--}
```
public final String getBody()
```


メールメッセージの本文を取得または設定します。


**Returns:**
java.lang.String
### setBody(String value) {#setBody-java.lang.String-}
```
public final void setBody(String value)
```


メールメッセージの本文を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Email プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ソース | java.lang.Object | 比較対象となる Email オブジェクト。 |
|

**Returns:**
boolean - 渡されたアドレスオブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Email のハッシュコード

