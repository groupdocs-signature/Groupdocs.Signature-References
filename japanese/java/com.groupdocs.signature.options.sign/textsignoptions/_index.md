---
title: "TextSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "テキスト署名オプションを表します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

テキスト署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | デフォルト値で SignTextOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | テキストを使用して SignTextOptions クラスの新しいインスタンスを初期化します。 |
|
## フィールド

| フィールド | 説明 |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getLeft()](#getLeft--) | 文書ページ上の署名の左側 X 位置（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
|
|  | [setLeft(int value)](#setLeft-int-) | 文書ページ上の署名の左側 X 位置（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
|
|  | [getTop()](#getTop--) | 文書ページ上の署名の上部 Y 位置（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
|
|  | [setTop(int value)](#setTop-int-) | 文書ページ上の署名の上部 Y 位置（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
|
|  | [getWidth()](#getWidth--) | 文書ページ上の署名の幅（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。
|
|  | [setWidth(int value)](#setWidth-int-) | 文書ページ上の署名の幅（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。
|
|  | [getHeight()](#getHeight--) | 文書ページ上の署名の高さ（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。
|
|  | [setHeight(int value)](#setHeight-int-) | 文書ページ上の署名の高さ（測定値） |
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | 左および上プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | 左および上プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | 幅および高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | 幅および高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。 |
|
|  | [getStretch()](#getStretch--) | 文書ページ上の伸縮モード。 |
|
|  | [setStretch(int value)](#setStretch-int-) | 文書ページ上の伸縮モード。 |
|
|  | [getRotationAngle()](#getRotationAngle--) | 文書ページ上の署名の回転角度（時計回り）。 |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | 文書ページ上の署名の回転角度（時計回り）。 |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 文書ページ上の署名の水平配置。 |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 文書ページ上の署名の水平配置。 |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 文書ページ上の署名の垂直配置。 |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 文書ページ上の署名の垂直配置。 |
|
|  | [getMargin()](#getMargin--) | 署名と文書の端との間のスペースを取得または設定します。 |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | 署名と文書の端との間のスペースを取得または設定します。 |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | 余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。 |
|
|  | [getTransparency()](#getTransparency--) | 署名の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 署名の透明度を取得または設定します（0.0（不透明）から 1.0（透明）までの値）。 |
|
|  | [getText()](#getText--) | 署名のテキストを取得または設定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 署名のテキストを取得または設定します。 |
|
|  | [getFont()](#getFont--) | 署名のフォントを取得または設定します。 |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | 署名のフォントを取得または設定します。 |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | 内部: このインスタンスが作成されたときのフォント、またはデフォルトフォントです。 |
|
|  | [getForeColor()](#getForeColor--) | 署名の前景色を取得または設定します。 |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | 署名の前景色を取得または設定します。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | テキスト署名実装のタイプを取得または設定します。 |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | テキスト署名実装のタイプを取得または設定します。 |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | 署名内のテキストの水平配置。 |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | 署名内のテキストの水平配置。 |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | 署名内のテキストの垂直配置。 |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | 署名内のテキストの垂直配置。 |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | テキスト署名を入れるテキストフォームフィールドのタイトルを取得または設定します。 |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | テキスト署名を入れるテキストフォームフィールドのタイトルを取得または設定します。 |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | テキスト署名を入れるフォームフィールドのタイプを取得または設定します。 |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | テキスト署名を入れるフォームフィールドのタイプを取得または設定します。 |
|
|  | [getShapeType()](#getShapeType--) | テキストを配置するシェイプのタイプを取得または設定します。 |
|
|  | [setShapeType(int value)](#setShapeType-int-) | テキストを配置するシェイプのタイプを取得または設定します。 |
|
|  | [getSignatureID()](#getSignatureID--) | 署名の一意の ID を取得または設定します。 |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 署名の一意の ID を取得または設定します。 |
|
|  | [getBorder()](#getBorder--) | 境界設定を指定します。 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 境界設定を指定します。 |
|
|  | [getBackground()](#getBackground--) | 署名の背景設定を取得または設定します。 |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | 署名の背景設定を取得または設定します。 |
|
|  | [getNative()](#getNative--) | ネイティブ属性を取得または設定します。 |
|
|  | [setNative(boolean value)](#setNative-boolean-) | ネイティブ属性を取得または設定します。 |
|
|  | [getShapePosition()](#getShapePosition--) | 形状が文書レイアウト内で表示される位置を定義します。 |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | 形状が文書レイアウト内で表示される位置を定義します。 |
|
|  | [validate()](#validate--) | オプションパラメータを検証する内部メソッドです。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


デフォルト値で SignTextOptions クラスの新しいインスタンスを初期化します。


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


テキストを使用して SignTextOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 署名テキスト。 |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


文書ページ上の署名の左側 X 位置（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
(水平揃えが指定されていない場合に機能します)。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


文書ページ上の署名の左側 X 位置（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
(水平揃えが指定されていない場合に機能します)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


文書ページ上の署名の上部 Y 位置（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
(垂直揃えが指定されていない場合に機能します)。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


文書ページ上の署名の上部 Y 位置（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の LocationMeasureType プロパティを参照してください)。
(垂直揃えが指定されていない場合に機能します)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


文書ページ上の署名の幅（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


文書ページ上の署名の幅（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


文書ページ上の署名の高さ（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


文書ページ上の署名の高さ（測定値）
(ピクセル、パーセント、またはミリメートルで、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) の SizeMeasureType プロパティを参照してください)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


左および上プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


左および上プロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


幅および高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


幅および高さプロパティの測定タイプ（ピクセル、パーセント、またはミリメートル）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


文書ページ上の伸縮モード。


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


文書ページ上の伸縮モード。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


文書ページ上の署名の回転角度（時計回り）。


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


文書ページ上の署名の回転角度（時計回り）。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


文書ページ上の署名の水平配置。


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


文書ページ上の署名の水平配置。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


文書ページ上の署名の垂直配置。


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


文書ページ上の署名の垂直配置。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


署名と文書の端との間のスペースを取得または設定します。
(水平または垂直揃えが指定されている場合にのみ機能します)。


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


署名と文書の端との間のスペースを取得または設定します。
(水平または垂直揃えが指定されている場合にのみ機能します)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


余白の測定タイプ（ピクセル、パーセント、またはミリメートル）を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


署名の透明度を取得または設定します (0.0（不透明）から 1.0（透明）までの値)。デフォルト値は 0（不透明）です。


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


署名の透明度を取得または設定します (0.0（不透明）から 1.0（透明）までの値)。デフォルト値は 0（不透明）です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getText() {#getText--}
```
public final String getText()
```


署名のテキストを取得または設定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


署名のテキストを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


署名のフォントを取得または設定します。


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


署名のフォントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


内部: このインスタンスが作成されたときのフォント、またはデフォルトフォントです。


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


署名の前景色を取得または設定します。


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


署名の前景色を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


テキスト署名実装のタイプを取得または設定します。


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


テキスト署名実装のタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


署名内のテキストの水平配置。
この機能は Image および Annotation 署名実装でのみサポートされます
(参照 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation プロパティ).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


署名内のテキストの水平配置。
この機能は Image および Annotation 署名実装でのみサポートされます
(参照 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation プロパティ).


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


署名内のテキストの垂直配置。
この機能は Image 署名実装でのみサポートされます
(参照 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation プロパティ).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


署名内のテキストの垂直配置。
この機能は Image 署名実装でのみサポートされます
(参照 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation プロパティ).


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


テキスト署名を入れるテキストフォームフィールドのタイトルを取得または設定します。
このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


テキスト署名を入れるテキストフォームフィールドのタイトルを取得または設定します。
このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


テキスト署名を入れるフォームフィールドのタイプを取得または設定します。
このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。
デフォルト値は AllTextTypes です。


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


テキスト署名を入れるフォームフィールドのタイプを取得または設定します。
このプロパティは SignatureImplementation = TextToFormField の場合にのみ使用できます。
デフォルト値は AllTextTypes です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


テキストを配置するシェイプのタイプを取得または設定します。
このプロパティは SignatureImplementation = TextStamp の場合にのみ使用できます。
デフォルト値は Rectangle です。


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


テキストを配置するシェイプのタイプを取得または設定します。
このプロパティは SignatureImplementation = TextStamp の場合にのみ使用できます。
デフォルト値は Rectangle です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


署名の一意の ID を取得または設定します。署名検証オプションで使用できます。このプロパティは Pdf ドキュメントでのみサポートされます


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


署名の一意の ID を取得または設定します。署名検証オプションで使用できます。このプロパティは Pdf ドキュメントでのみサポートされます


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


境界設定を指定します。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


境界設定を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


署名の背景設定を取得または設定します。


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


署名の背景設定を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


ネイティブ属性を取得または設定します。設定すると、ドキュメント固有の署名を使用できる場合があります。
WordProcessing ドキュメント用のネイティブテキスト透かしは、たとえば通常のものとは異なります。


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


ネイティブ属性を取得または設定します。設定すると、ドキュメント固有の署名を使用できる場合があります。
WordProcessing ドキュメント用のネイティブテキスト透かしは、たとえば通常のものとは異なります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


形状が文書レイアウト内で表示される位置を定義します。


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


形状が文書レイアウト内で表示される位置を定義します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### validate() {#validate--}
```
public void validate()
```


オプションパラメータを検証する内部メソッドです。


### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
