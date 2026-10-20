---
title: "SquareBorder"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "正方形スタンプラインの境界線プロパティを保持するインスタンス。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.stamps/squareborder/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.Border](../../com.groupdocs.signature.domain/border)
```
public class SquareBorder extends Border
```

正方形スタンプラインの境界線プロパティを保持するインスタンス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SquareBorder(double radius)](#SquareBorder-double-) | 丸みを帯びたコーナー半径を持つ SquareBorderLine を作成します。 |
|
|  | [SquareBorder(Corners corners)](#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-) | コーナー半径の値を持つ SquareBorderLine を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getRadius()](#getRadius--) | 四角形のコーナー半径を取得または設定します。 |
|
|  | [setRadius(Corners value)](#setRadius-com.groupdocs.signature.domain.stamps.Corners-) | 四角形のコーナー半径を取得または設定します。 |
|
### SquareBorder(double radius) {#SquareBorder-double-}
```
public SquareBorder(double radius)
```


丸みを帯びたコーナー半径を持つ SquareBorderLine を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 半径 | double | 四角形のコーナー半径。 |
|

### SquareBorder(Corners corners) {#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-}
```
public SquareBorder(Corners corners)
```


コーナー半径の値を持つ SquareBorderLine を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | corners | [Corners](../../com.groupdocs.signature.domain.stamps/corners) | 四角形のコーナー半径。 |
|

### getRadius() {#getRadius--}
```
public final Corners getRadius()
```


四角形のコーナー半径を取得または設定します。


**Returns:**
[Corners](../../com.groupdocs.signature.domain.stamps/corners)
### setRadius(Corners value) {#setRadius-com.groupdocs.signature.domain.stamps.Corners-}
```
public final void setRadius(Corners value)
```


四角形のコーナー半径を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Corners](../../com.groupdocs.signature.domain.stamps/corners) |  |

