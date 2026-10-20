---
title: "BaseSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名の基底クラスを説明します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

署名の基底クラスを説明します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | 署名のタイプを指定します。 |
|
|  | [getPageNumber()](#getPageNumber--) | 署名が見つかったページを指定します。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 署名が見つかったページを指定します。 |
|
|  | [getSignatureId()](#getSignatureId--) | Update または Delete メソッドでドキュメント内の署名を変更するためのユニークな署名識別子です。 |
|
|  | [isSignature()](#isSignature--) | このコンポーネントが署名かドキュメントコンテンツかを示すフラグを取得または設定します。 |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | このコンポーネントが署名かドキュメントコンテンツかを示すフラグを取得または設定します。 |
|
|  | [getDeleted()](#getDeleted--) | この署名がドキュメントから削除されたかどうかを示すフラグを取得または設定します。 |
|
|  | [getCreatedOn()](#getCreatedOn--) | 署名の作成日を取得または設定します。 |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | 署名の作成日を取得または設定します。 |
|
|  | [getModifiedOn()](#getModifiedOn--) | 署名の変更日を取得または設定します。 |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | 署名の変更日を取得または設定します。 |
|
|  | [getTop()](#getTop--) | 署名の上位置を指定します。 |
|
|  | [setTop(int value)](#setTop-int-) | 署名の上位置を指定します。 |
|
|  | [getLeft()](#getLeft--) | 署名の左位置を指定します。 |
|
|  | [setLeft(int value)](#setLeft-int-) | 署名の左位置を指定します。 |
|
|  | [getWidth()](#getWidth--) | 署名の幅を指定します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | 署名の幅を指定します。 |
|
|  | [getHeight()](#getHeight--) | 署名の高さを指定します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | 署名の高さを指定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


署名のタイプを指定します。デジタル署名はこのプロパティを持ちます。


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


署名が見つかったページを指定します。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


署名が見つかったページを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


Update または Delete メソッドでドキュメント内の署名を変更するためのユニークな署名識別子です。
Sign または Search メソッドが呼び出された後、このプロパティは自動的に設定されます。
このプロパティが以前に保存されている場合、署名を操作するために手動で設定できます。


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


このコンポーネントが署名かドキュメントコンテンツかを示すフラグを取得または設定します。
このプロパティは Update メソッドと共に使用され、要素を署名 (true) またはドキュメント要素 (false) に設定します。


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


このコンポーネントが署名かドキュメントコンテンツかを示すフラグを取得または設定します。
このプロパティは Update メソッドと共に使用され、要素を署名 (true) またはドキュメント要素 (false) に設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


この署名がドキュメントから削除されたかどうかを示すフラグを取得または設定します。
このプロパティは、削除された署名のリストを保持するために、ドキュメント履歴ログレコードでのみ使用されます。


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


署名の作成日を取得または設定します。


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


署名の作成日を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


署名の変更日を取得または設定します。


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


署名の変更日を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


署名の上位置を指定します。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


署名の上位置を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


署名の左位置を指定します。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


署名の左位置を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


署名の幅を指定します。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


署名の幅を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


署名の高さを指定します。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


署名の高さを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


署名プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signature | java.lang.Object | 比較対象となる Signature オブジェクト。 |
|

**Returns:**
boolean - 渡された signature オブジェクトが同じ型であり、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
