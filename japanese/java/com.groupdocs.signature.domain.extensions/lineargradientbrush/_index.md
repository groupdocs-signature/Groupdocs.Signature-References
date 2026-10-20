---
title: "LinearGradientBrush"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "線形グラデーションブラシを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.extensions/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class LinearGradientBrush extends Brush
```

線形グラデーションブラシを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [LinearGradientBrush()](#LinearGradientBrush--) | LinearGradientBrush クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [LinearGradientBrush(Color startColor, Color endColor, float angle)](#LinearGradientBrush-java.awt.Color-java.awt.Color-float-) | LinearGradientBrush クラスの新しいインスタンスを初期化します。 |
|
|  | [LinearGradientBrush(String startColor, String endColor, float angle)](#LinearGradientBrush-java.lang.String-java.lang.String-float-) | LinearGradientBrush クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStartColor()](#getStartColor--) | 開始グラデーションの色を取得または設定します。 |
|
|  | [setStartColor(Color value)](#setStartColor-java.awt.Color-) | 開始グラデーションの色を取得または設定します。 |
|
|  | [setStartColor(String value)](#setStartColor-java.lang.String-) | 開始グラデーションの色を取得または設定します。 |
|
|  | [getEndColor()](#getEndColor--) | 終了グラデーションの色を取得または設定します。 |
|
|  | [setEndColor(Color value)](#setEndColor-java.awt.Color-) | 終了グラデーションの色を取得または設定します。 |
|
|  | [setEndColor(String value)](#setEndColor-java.lang.String-) | 終了グラデーションの色を取得または設定します。 |
|
|  | [getAngle()](#getAngle--) | グラデーション角度を取得または設定します。 |
|
|  | [setAngle(float value)](#setAngle-float-) | グラデーション角度を取得または設定します。 |
|
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


LinearGradientBrush クラスの新しいインスタンスをデフォルト値で初期化します。


### LinearGradientBrush(Color startColor, Color endColor, float angle) {#LinearGradientBrush-java.awt.Color-java.awt.Color-float-}
```
public LinearGradientBrush(Color startColor, Color endColor, float angle)
```


LinearGradientBrush クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | startColor | java.awt.Color | 開始色。 |
|
|  | endColor | java.awt.Color | 終了色。 |
|
|  | angle | float | 角度。デフォルト値は0です。 |
|

### LinearGradientBrush(String startColor, String endColor, float angle) {#LinearGradientBrush-java.lang.String-java.lang.String-float-}
```
public LinearGradientBrush(String startColor, String endColor, float angle)
```


LinearGradientBrush クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | startColor | java.lang.String | 開始色。 |
|
|  | endColor | java.lang.String | 終了色。 |
|
|  | angle | float | 角度。デフォルト値は0です。 |
|

### getStartColor() {#getStartColor--}
```
public final Color getStartColor()
```


開始グラデーションの色を取得または設定します。


**Returns:**
java.awt.Color
### setStartColor(Color value) {#setStartColor-java.awt.Color-}
```
public final void setStartColor(Color value)
```


開始グラデーションの色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setStartColor(String value) {#setStartColor-java.lang.String-}
```
public final void setStartColor(String value)
```


開始グラデーションの色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getEndColor() {#getEndColor--}
```
public final Color getEndColor()
```


終了グラデーションの色を取得または設定します。


**Returns:**
java.awt.Color
### setEndColor(Color value) {#setEndColor-java.awt.Color-}
```
public final void setEndColor(Color value)
```


終了グラデーションの色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setEndColor(String value) {#setEndColor-java.lang.String-}
```
public final void setEndColor(String value)
```


終了グラデーションの色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


グラデーション角度を取得または設定します。


**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


グラデーション角度を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | float |  |

