---
title: "Background"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "背景の外観を表します"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

背景の外観を表します

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Background()](#Background--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getColor()](#getColor--) | 署名の背景色を取得または設定します。 |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 署名の背景色を取得または設定します。 |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 署名の背景色を取得または設定します。 |
|
|  | [getTransparency()](#getTransparency--) | 背景の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 背景の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [getBrush()](#getBrush--) | 背景ブラシを取得または設定します。 |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | 背景ブラシを取得または設定します。 |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


署名の背景色を取得または設定します。


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


署名の背景色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


署名の背景色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


背景の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


背景の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


背景ブラシを取得または設定します。デフォルト値は null です。
このプロパティは Brush オブジェクトの実装インスタンスを期待します
さまざまな Brush クラスを参照してください


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


背景ブラシを取得または設定します。デフォルト値は null です。
このプロパティは Brush オブジェクトの実装インスタンスを期待します
さまざまな Brush クラスを参照してください


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

