---
title: "TextShadow"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "テキスト署名のテキストシャドウプロパティを表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

テキスト署名のテキストシャドウプロパティを表します。
結果は署名タイプや文書形式に応じて変わる場合があります。
TextShadow は、すべてのサポート対象文書タイプで TextAsImage 署名と併用することが推奨されます、
また、シンプルな TextSignature と Watermark 用の TextSignature を Cells（.xslx） と Slides（.pptx） に使用する場合にも推奨されます。
Words（.docx） 用のシンプルな TextSignature も推奨されますが、機能は制限されています。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | デフォルトオプションで TextShadow を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDistance()](#getDistance--) | テキストから影までの距離を取得または設定します。 |
|
|  | [setDistance(double value)](#setDistance-double-) | テキストから影までの距離を取得または設定します。 |
|
|  | [getAngle()](#getAngle--) | テキストに対する影の配置角度を取得または設定します。 |
|
|  | [setAngle(double value)](#setAngle-double-) | テキストに対する影の配置角度を取得または設定します。 |
|
|  | [getColor()](#getColor--) | 影の色を取得または設定します。 |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 影の色を取得または設定します。 |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 影の色を取得または設定します。 |
|
|  | [getTransparency()](#getTransparency--) | 影の透明度を取得または設定します。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 影の透明度を取得または設定します。 |
|
|  | [getBlur()](#getBlur--) | 影のぼかしを取得または設定します。 |
|
|  | [setBlur(double value)](#setBlur-double-) | 影のぼかしを取得または設定します。 |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


デフォルトオプションで TextShadow を作成します。


### getDistance() {#getDistance--}
```
public final double getDistance()
```


テキストから影までの距離を取得または設定します。
既定値は 1 です。


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


テキストから影までの距離を取得または設定します。
既定値は 1 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


テキストに対する影の配置角度を取得または設定します。
既定値は 0 です。


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


テキストに対する影の配置角度を取得または設定します。
既定値は 0 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


影の色を取得または設定します。
既定値は Black です。


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


影の色を取得または設定します。
既定値は Black です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


影の色を取得または設定します。
既定値は Black です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


影の透明度を取得または設定します。
既定値は 0 です。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


影の透明度を取得または設定します。
既定値は 0 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


影のぼかしを取得または設定します。
既定値は 4 です。


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


影のぼかしを取得または設定します。
既定値は 4 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

