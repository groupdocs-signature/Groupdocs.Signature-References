---
title: "タイムスタンプ"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "サードパーティサイトからタイムスタンプを取得するためのデータを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

サードパーティサイトからタイムスタンプを取得するためのデータを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | 新しいタイムスタンプ構造体をインスタンス化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getUrl()](#getUrl--) | サードパーティサイトの URL。 |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | サードパーティサイトの URL。 |
|
|  | [getUser()](#getUser--) | ユーザー。 |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | ユーザー。 |
|
|  | [getPassword()](#getPassword--) | パスワード。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワード。 |
|
| [CloneTo(TimeStamp that)](#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(TimeStamp obj1, TimeStamp obj2)](#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
### TimeStamp() {#TimeStamp--}
```
public TimeStamp()
```


### TimeStamp(String url, String user, String password) {#TimeStamp-java.lang.String-java.lang.String-java.lang.String-}
```
public TimeStamp(String url, String user, String password)
```


新しいタイムスタンプ構造体をインスタンス化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | URL | java.lang.String | サードパーティサイトの URL。 |
|
|  | ユーザー | java.lang.String | ユーザー。 |
|
|  | パスワード | java.lang.String | パスワード。 |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


サードパーティサイトの URL。


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


サードパーティサイトの URL。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


ユーザー。


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


ユーザー。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワード。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワード。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| that | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### Clone() {#Clone--}
```
public TimeStamp Clone()
```




**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(TimeStamp obj1, TimeStamp obj2) {#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public static boolean equals(TimeStamp obj1, TimeStamp obj2)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
