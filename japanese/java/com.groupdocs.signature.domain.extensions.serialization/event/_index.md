---
title: "イベント"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "標準 QRコード イベントの詳細を表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/event/
---
**Inheritance:**
java.lang.Object
```
public final class Event
```

標準 QRコード イベントの詳細を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Event()](#Event--) | デフォルト値で Event インスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getTitle()](#getTitle--) | イベントのタイトルを取得または設定します。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | イベントのタイトルを取得または設定します。 |
|
|  | [getDescription()](#getDescription--) | 説明を取得または設定します。 |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | 説明を取得または設定します。 |
|
|  | [getLocation()](#getLocation--) | イベントの場所を取得または設定します。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | イベントの場所を取得または設定します。 |
|
|  | [getStartDate()](#getStartDate--) | イベントの開始日時を取得または設定します。 |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | イベントの開始日時を取得または設定します。 |
|
|  | [getEndDate()](#getEndDate--) | イベントの終了日時を取得または設定します。 |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | イベントの終了日時を取得または設定します。 |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Event プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### Event() {#Event--}
```
public Event()
```


デフォルト値で Event インスタンスを作成します。


### getTitle() {#getTitle--}
```
public final String getTitle()
```


イベントのタイトルを取得または設定します。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


イベントのタイトルを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


説明を取得または設定します。


**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


説明を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


イベントの場所を取得または設定します。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


イベントの場所を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


イベントの開始日時を取得または設定します。


**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


イベントの開始日時を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


イベントの終了日時を取得または設定します。


**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


イベントの終了日時を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Event プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ソース | java.lang.Object | 比較対象となる Event オブジェクトです。 |
|

**Returns:**
boolean - 渡された Event オブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Event のハッシュコード

