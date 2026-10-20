---
title: "Corners"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "正方形のグラフィックオブジェクトの角を表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

正方形のグラフィックオブジェクトの角を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Corners()](#Corners--) | ゼロ値を使用して Corners クラスの新しいインスタンスを初期化します。 |
|
|  | [Corners(double all)](#Corners-double-) | すべてのコーナーに提供された値を使用して Corners クラスの新しいインスタンスを初期化します。 |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | 提供された値を使用して Corners クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
|  | [Empty](#Empty) | データのない Corners オブジェクトを提供します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAll()](#getAll--) | すべてのコーナーの値を取得または設定します。 |
|
|  | [setAll(double value)](#setAll-double-) | すべてのコーナーの値を取得または設定します。 |
|
|  | [getTopLeft()](#getTopLeft--) | 左上コーナーの値を取得または設定します。 |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | 左上コーナーの値を取得または設定します。 |
|
|  | [getTopRight()](#getTopRight--) | 右上コーナーの値を取得または設定します。 |
|
|  | [setTopRight(double value)](#setTopRight-double-) | 右上コーナーの値を取得または設定します。 |
|
|  | [getBottomLeft()](#getBottomLeft--) | 左下コーナーの値を取得または設定します。 |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | 左下コーナーの値を取得または設定します。 |
|
|  | [getBottomRight()](#getBottomRight--) | 右下コーナーの値を取得または設定します。 |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | 右下コーナーの値を取得または設定します。 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | equals メソッドをオーバーライドする |
|
|  | [hashCode()](#hashCode--) | 一意なハッシュコード値の取得をオーバーライドする |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドする。 |
|
### Corners() {#Corners--}
```
public Corners()
```


ゼロ値を使用して Corners クラスの新しいインスタンスを初期化します。


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


すべてのコーナーに提供された値を使用して Corners クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | すべて | double | すべての角のパディングに使用される値です。 |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


提供された値を使用して Corners クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | topLeft | double | 左上隅の値です。 |
|
|  | topRight | double | 右上隅の値です。 |
|
|  | bottomLeft | double | 左下隅の値です。 |
|
|  | bottomRight | double | 右下隅の値です。 |
|

### Empty {#Empty}
```
public static final Corners Empty
```


データのない Corners オブジェクトを提供します。


### getAll() {#getAll--}
```
public final double getAll()
```


すべてのコーナーの値を取得または設定します。
右上などの部分的な角を変更すると、このプロパティは 0 に設定されます；


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


すべてのコーナーの値を取得または設定します。
右上などの部分的な角を変更すると、このプロパティは 0 に設定されます；


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


左上コーナーの値を取得または設定します。


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


左上コーナーの値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


右上コーナーの値を取得または設定します。


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


右上コーナーの値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


左下コーナーの値を取得または設定します。


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


左下コーナーの値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


右下コーナーの値を取得または設定します。


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


右下コーナーの値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


このオブジェクトのコピーを取得します。


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


equals メソッドをオーバーライドする


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 比較対象のインスタンスです。 |
|

**Returns:**
boolean - オブジェクトのプロパティが等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


一意なハッシュコード値の取得をオーバーライドする


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドする。


**Returns:**
java.lang.String -
