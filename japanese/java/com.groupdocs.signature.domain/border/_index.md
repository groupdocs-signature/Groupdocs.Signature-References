---
title: "Border"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "境界線プロパティを保持するインスタンスです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

境界線プロパティを保持するインスタンスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [Border()](#Border--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | 署名の境界線スタイルを取得または設定します。 |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | 署名の境界線スタイルを取得または設定します。 |
|
|  | [getTransparency()](#getTransparency--) | 署名の境界線の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 署名の境界線の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [getWeight()](#getWeight--) | 署名の境界線の太さを取得または設定します。 |
|
|  | [setWeight(double value)](#setWeight-double-) | 署名の境界線の太さを取得または設定します。 |
|
|  | [getColor()](#getColor--) | 署名の境界線の色を取得または設定します。 |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 署名の境界線の色を取得または設定します。 |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 署名の境界線の色を取得または設定します。 |
|
|  | [getVisible()](#getVisible--) | 境界線の表示/非表示を取得または設定します。 |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | IClonable インターフェイスを実装します |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


署名の境界線スタイルを取得または設定します。


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


署名の境界線スタイルを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


署名の境界線の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


署名の境界線の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


署名の境界線の太さを取得または設定します。


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


署名の境界線の太さを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


署名の境界線の色を取得または設定します。


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


署名の境界線の色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


署名の境界線の色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


境界線の表示/非表示を取得または設定します。


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


IClonable インターフェイスを実装します


**Returns:**
java.lang.Object - 同じプロパティを持つ新しく作成された Border インスタンス

