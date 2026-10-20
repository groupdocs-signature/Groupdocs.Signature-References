---
title: "StampSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スタンプ署名オプションを表します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

スタンプ署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | デフォルト値で StampSignOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | 配置オプションで StampSignOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getStampType()](#getStampType--) | スタンプのタイプを取得または設定します。 |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | スタンプのタイプを取得または設定します。 |
|
|  | [getOuterLines()](#getOuterLines--) | 外側の線のリストは同心円として描画されます。 |
|
|  | [getInnerLines()](#getInnerLines--) | 内側の線のリストは矩形の集合として描画されます。 |
|
|  | [getBackground()](#getBackground--) | スタンプの背景を取得または設定します。 |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | スタンプの背景を取得または設定します。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 署名の背景色を取得または設定します。 |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 署名の背景色を取得または設定します。 |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | 署名の背景ブラシを取得または設定します。 |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | 署名の背景ブラシを取得または設定します。 |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | 署名の背景色の切り取りタイプを取得または設定します。 |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | 署名の背景色の切り取りタイプを取得または設定します。 |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | 署名の背景画像の切り取りタイプを取得または設定します。 |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | 署名の背景画像の切り取りタイプを取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライド |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


デフォルト値で StampSignOptions クラスの新しいインスタンスを初期化します。


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


配置オプションで StampSignOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 左 | int | Stamp Signature の左上端の X 座標 |
|
|  | 上 | int | Stamp Signature の左上端の Y 座標 |
|
|  | 幅 | int | Stamp Signature の幅 |
|
|  | 高さ | int | Stamp Signature の高さ |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


スタンプのタイプを取得または設定します。
デフォルト値は Round です。


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


スタンプのタイプを取得または設定します。
デフォルト値は Round です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


外側の線のリストは同心円として描画されます。


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


内側の線のリストは矩形の集合として描画されます。


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


スタンプの背景を取得または設定します。


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


スタンプの背景を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


署名の背景色を取得または設定します。


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


署名の背景色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


署名の背景ブラシを取得または設定します。デフォルト値は null です。


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


署名の背景ブラシを取得または設定します。デフォルト値は null です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


署名の背景色の切り取りタイプを取得または設定します。


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


署名の背景色の切り取りタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


署名の背景画像の切り取りタイプを取得または設定します。


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


署名の背景画像の切り取りタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライド


**Returns:**
java.lang.String -
