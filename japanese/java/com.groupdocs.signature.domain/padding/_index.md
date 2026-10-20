---
title: "Padding"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "要素に関連付けられたパディングまたはマージン情報を表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

要素に関連付けられたパディングまたはマージン情報を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Padding()](#Padding--) | ゼロ値を使用して Padding クラスの新しいインスタンスを初期化します。 |
|
|  | [Padding(int all)](#Padding-int-) | 提供されたパディングサイズをすべてのエッジに使用して Padding クラスの新しいインスタンスを初期化します。 |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | 提供されたパディングサイズを使用して Padding クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Empty](#Empty) | パディングなしの Padding オブジェクトを提供します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべてのエッジのパディング値を取得または設定します。 |
|
|  | [setAll(int value)](#setAll-int-) | すべてのエッジのパディング値を取得または設定します。 |
|
|  | [getLeft()](#getLeft--) | 左エッジのパディング値を取得または設定します。 |
|
|  | [setLeft(int value)](#setLeft-int-) | 左エッジのパディング値を取得または設定します。 |
|
|  | [getRight()](#getRight--) | 右エッジのパディング値を取得または設定します。 |
|
|  | [setRight(int value)](#setRight-int-) | 右エッジのパディング値を取得または設定します。 |
|
|  | [getTop()](#getTop--) | 上エッジのパディング値を取得または設定します。 |
|
|  | [setTop(int value)](#setTop-int-) | 上エッジのパディング値を取得または設定します。 |
|
|  | [getBottom()](#getBottom--) | 下エッジのパディング値を取得または設定します。 |
|
|  | [setBottom(int value)](#setBottom-int-) | 下エッジのパディング値を取得または設定します。 |
|
|  | [getHorizontal()](#getHorizontal--) | 右と左のエッジの合計パディングを取得します。 |
|
|  | [getVertical()](#getVertical--) | 上と下のエッジの合計パディングを取得します。 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドします |
|
### Padding() {#Padding--}
```
public Padding()
```


ゼロ値を使用して Padding クラスの新しいインスタンスを初期化します。


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


提供されたパディングサイズをすべてのエッジに使用して Padding クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | すべて | int | すべてのエッジのパディングに使用される測定単位の数です。 |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


提供されたパディングサイズを使用して Padding クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 左 | int | 左側のパディングサイズです。 |
|
|  | 右 | int | 右側のパディングサイズです。 |
|
|  | 上 | int | 上側のパディングサイズです。 |
|
|  | 下 | int | 下側のパディングサイズです。 |
|

### Empty {#Empty}
```
public static final Padding Empty
```


パディングなしの Padding オブジェクトを提供します。


### getAll() {#getAll--}
```
public final int getAll()
```


すべてのエッジのパディング値を取得または設定します。
左や上などの部分的なエッジを変更すると、このプロパティは 0 になります；


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


すべてのエッジのパディング値を取得または設定します。
左や上などの部分的なエッジを変更すると、このプロパティは 0 になります；


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


左エッジのパディング値を取得または設定します。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


左エッジのパディング値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


右エッジのパディング値を取得または設定します。


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


右エッジのパディング値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


上エッジのパディング値を取得または設定します。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


上エッジのパディング値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


下エッジのパディング値を取得または設定します。


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


下エッジのパディング値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


右と左のエッジの合計パディングを取得します。


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


上と下のエッジの合計パディングを取得します。


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


このオブジェクトのコピーを取得します。


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドします


**Returns:**
java.lang.String -
