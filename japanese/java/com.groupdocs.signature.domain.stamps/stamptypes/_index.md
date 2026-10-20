---
title: "StampTypes"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スタンプタイプのコンテナ。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.domain.stamps/stamptypes/
---
**Inheritance:**
java.lang.Object
```
public class StampTypes
```

スタンプタイプのコンテナ。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [StampTypes()](#StampTypes--) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Round](#Round) | 丸形スタンプタイプオブジェクト。 |
|
|  | [Square](#Square) | 四角形スタンプタイプオブジェクト。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAllTypes()](#getAllTypes--) | すべてのスタンプタイプ。 |
|
|  | [parse(String parsingType)](#parse-java.lang.String-) | pasringType 名のスタンプタイプを返します。 |
|
|  | [tryParse(String parsingType)](#tryParse-java.lang.String-) | pasringType 名のスタンプタイプを返します。 |
|
### StampTypes() {#StampTypes--}
```
public StampTypes()
```


### Round {#Round}
```
public static final StampType Round
```


丸形スタンプタイプオブジェクト。


### Square {#Square}
```
public static final StampType Square
```


四角形スタンプタイプオブジェクト。


### getAllTypes() {#getAllTypes--}
```
public static StampType[] getAllTypes()
```


すべてのスタンプタイプ。


**Returns:**
com.groupdocs.signature.domain.stamps.StampType[]
### parse(String parsingType) {#parse-java.lang.String-}
```
public static StampType parse(String parsingType)
```


pasringType 名のスタンプタイプを返します。スタンプ名が不明な場合は例外がスローされます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | parsingType | java.lang.String | スタンプタイプ名のソース文字列。 |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

### tryParse(String parsingType) {#tryParse-java.lang.String-}
```
public static StampType tryParse(String parsingType)
```


pasringType 名のスタンプタイプを返します。スタンプ名が不明な場合、例外はスローされず、メソッドは null 値を返します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | parsingType | java.lang.String | スタンプタイプ名のソース文字列。 |
|

**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype) - StampType instance.

