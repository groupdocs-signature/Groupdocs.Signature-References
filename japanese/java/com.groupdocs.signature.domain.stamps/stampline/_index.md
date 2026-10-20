---
title: "StampLine"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スタンプラインのプロパティを指定します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

スタンプラインのプロパティを指定します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [StampLine()](#StampLine--) | デフォルト値で StampLine を作成します。 |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | テキストで StampLine を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getHeight()](#getHeight--) | Stamp の行の高さを取得または設定します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | Stamp の行の高さを取得または設定します。 |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 署名の背景色を取得または設定します。 |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 署名の背景色を取得または設定します。 |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | 署名の背景色を取得または設定します。 |
|
|  | [getText()](#getText--) | スタンプラインのテキストを取得または設定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | スタンプラインのテキストを取得または設定します。 |
|
|  | [getFont()](#getFont--) | スタンプラインテキストのフォントを取得または設定します。 |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | スタンプラインテキストのフォントを取得または設定します。 |
|
|  | [getTextColor()](#getTextColor--) | 署名のテキスト色を取得または設定します。 |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | 署名のテキスト色を取得または設定します。 |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | 署名のテキスト色を取得または設定します。 |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | テキストの下部インテントを取得または設定します。 |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | テキストの下部インテントを取得または設定します。 |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | テキストの繰り返しタイプを取得または設定します。 |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | テキストの繰り返しタイプを取得または設定します。 |
|
|  | [getOuterBorder()](#getOuterBorder--) | 外側の境界線を設定します。 |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | 外側の境界線を設定します。 |
|
|  | [getInnerBorder()](#getInnerBorder--) | 内部の境界線を設定します。 |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | 内部の境界線を設定します。 |
|
|  | [getVisible()](#getVisible--) | スタンプラインの表示状態を取得および設定します。 |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | スタンプラインの表示状態を取得および設定します。 |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


デフォルト値で StampLine を作成します。


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


テキストで StampLine を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | スタンプラインのテキスト。 |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Stamp の行の高さを取得または設定します。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stamp の行の高さを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


署名の背景色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


スタンプラインのテキストを取得または設定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


スタンプラインのテキストを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


スタンプラインテキストのフォントを取得または設定します。


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


スタンプラインテキストのフォントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


署名のテキスト色を取得または設定します。


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


署名のテキスト色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


署名のテキスト色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


テキストの下部インテントを取得または設定します。


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


テキストの下部インテントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


テキストの繰り返しタイプを取得または設定します。


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


テキストの繰り返しタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


外側の境界線を設定します。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


外側の境界線を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


内部の境界線を設定します。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


内部の境界線を設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


スタンプラインの表示状態を取得および設定します。


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


スタンプラインの表示状態を取得および設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

