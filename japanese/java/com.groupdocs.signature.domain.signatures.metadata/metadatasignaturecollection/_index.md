---
title: "MetadataSignatureCollection"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "メタデータ署名オブジェクトのコレクション。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class MetadataSignatureCollection implements Iterable<MetadataSignature>
```

メタデータ署名オブジェクトのコレクション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [MetadataSignatureCollection()](#MetadataSignatureCollection--) | Metadata 署名のコレクションを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCount()](#getCount--) | コレクション内の項目数を取得します。 |
|
|  | [clear()](#clear--) | コレクションからすべての項目を削除します。 |
|
|  | [contains(String name)](#contains-java.lang.String-) | コレクションに指定された名前の Metadata が存在する場合は true を返します。 |
|
|  | [indexOf(String name)](#indexOf-java.lang.String-) | 名前でプロパティのインデックスを取得します。 |
|
|  | [remove(String name)](#remove-java.lang.String-) | コレクションから指定された名前のメタデータ署名を削除します。 |
|
|  | [removeAt(int index)](#removeAt-int-) | 指定されたインデックスのメタデータ署名を削除します。 |
|
|  | [add(MetadataSignature signature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | メタデータ署名オブジェクトをコレクションに追加します。 |
|
|  | [addRange(MetadataSignature[] signatures)](#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---) | メタデータ署名コレクションを追加します。 |
|
|  | [deepClone()](#deepClone--) | メタデータ署名アイテムを含むメタデータ署名コレクションクラスをクローンします。 |
|
### MetadataSignatureCollection() {#MetadataSignatureCollection--}
```
public MetadataSignatureCollection()
```


Metadata 署名のコレクションを作成します。


### getCount() {#getCount--}
```
public final int getCount()
```


コレクション内の項目数を取得します。


**Returns:**
int
### clear() {#clear--}
```
public final void clear()
```


コレクションからすべての項目を削除します。


### contains(String name) {#contains-java.lang.String-}
```
public final boolean contains(String name)
```


コレクションに指定された名前の Metadata が存在する場合は true を返します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | プロパティの大文字小文字を区別しない名前です。 |
|

**Returns:**
boolean - コレクションにメタデータが存在する場合は true、そうでない場合は false。

### indexOf(String name) {#indexOf-java.lang.String-}
```
public final int indexOf(String name)
```


名前でプロパティのインデックスを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | MetadataSignature の大文字小文字を区別しない名前です。 |
|

**Returns:**
int - ゼロベースのインデックスです。見つからない場合は負の値。

### remove(String name) {#remove-java.lang.String-}
```
public final boolean remove(String name)
```


コレクションから指定された名前のメタデータ署名を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Metadata Signature の大文字小文字を区別しない名前です。 |
|

**Returns:**
boolean -
### removeAt(int index) {#removeAt-int-}
```
public final boolean removeAt(int index)
```


指定されたインデックスのメタデータ署名を削除します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | インデックス | int | ゼロベースのインデックスです。 |
|

**Returns:**
boolean
### add(MetadataSignature signature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final void add(MetadataSignature signature)
```


メタデータ署名オブジェクトをコレクションに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | コレクションに追加されるメタデータ署名です。 |

<br />

*** ** * ** ***

名前の値が既存のコレクション全体で一意でない場合、例外をスローします。

<br />

|

### addRange(MetadataSignature[] signatures) {#addRange-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature---}
```
public final void addRange(MetadataSignature[] signatures)
```


メタデータ署名コレクションを追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatures | [MetadataSignature\[\]](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 追加する署名のコレクションです。 |

<br />

*** ** * ** ***

名前の値が既存のコレクション全体で一意でない場合、例外をスローします。

<br />

|

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


メタデータ署名アイテムを含むメタデータ署名コレクションクラスをクローンします。


**Returns:**
java.lang.Object - クローンされた署名アイテムを持つコピーインスタンスを返します

