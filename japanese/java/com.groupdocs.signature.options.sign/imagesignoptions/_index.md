---
title: "ImageSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像署名オプションを表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

画像署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | ImageSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | ImageSignOptions クラスの新しいインスタンスを画像ファイルで初期化します。 |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | ImageSignOptions クラスの新しいインスタンスを画像ストリームで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | 署名画像ファイルのパスを取得または設定します。 |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | 署名画像ファイルのパスを取得または設定します。 |
|
|  | [getImageStream()](#getImageStream--) | 署名画像ストリームを取得または設定します。 |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 署名画像ストリームを取得または設定します。 |
|
|  | [getLeft()](#getLeft--) | 文書ページ上の署名の左側 X 位置（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
|
|  | [setLeft(int value)](#setLeft-int-) | 文書ページ上の署名の左側 X 位置（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
|
|  | [getTop()](#getTop--) | 文書ページ上の署名の上部 Y 位置（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
|
|  | [setTop(int value)](#setTop-int-) | 文書ページ上の署名の上部 Y 位置（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
|
|  | [getWidth()](#getWidth--) | 文書ページ上の署名の幅（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)。
|
|  | [setWidth(int value)](#setWidth-int-) | 文書ページ上の署名の幅（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)。
|
|  | [getHeight()](#getHeight--) | 文書ページ上の署名の高さ（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType を参照)。
|
|  | [setHeight(int value)](#setHeight-int-) | 文書ページ上の署名の高さ（測定値） |
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType を参照)。
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
|  | [getShapePosition()](#getShapePosition--) | 形状が文書レイアウト内で表示される位置を定義します。 |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | 形状が文書レイアウト内で表示される位置を定義します。 |
|
|  | [getRectangle()](#getRectangle--) | 文書上に画像を配置する領域の矩形。 |
|
|  | [getBorder()](#getBorder--) | 境界設定を指定します。 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 境界設定を指定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Base64 からの事前定義された画像を使用して、ImageSignOptions クラスの新しいインスタンスを作成します。 |
|
|  | [dispose()](#dispose--) | 内部リソースをクリアします |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


ImageSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


ImageSignOptions クラスの新しいインスタンスを画像ファイルで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | 画像ファイルパス |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


ImageSignOptions クラスの新しいインスタンスを画像ストリームで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | 画像ストリーム |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


署名画像ファイルのパスを取得または設定します。
このプロパティは ImageStream が指定されていない場合にのみ使用されます。


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


署名画像ファイルのパスを取得または設定します。
このプロパティは ImageStream が指定されていない場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


署名画像ストリームを取得または設定します。
このプロパティが指定されている場合、常に ImageGuid の代わりに使用されます。


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


署名画像ストリームを取得または設定します。
このプロパティが指定されている場合、常に ImageGuid の代わりに使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


文書ページ上の署名の左側 X 位置（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
(水平揃えが指定されていない場合に機能します)。


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


文書ページ上の署名の左側 X 位置（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
(水平揃えが指定されていない場合に機能します)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


文書ページ上の署名の上部 Y 位置（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
(垂直揃えが指定されていない場合に機能します)。


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


文書ページ上の署名の上部 Y 位置（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType を参照)。
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
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


文書ページ上の署名の幅（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


文書ページ上の署名の高さ（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType を参照)。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


文書ページ上の署名の高さ（測定値）
(ピクセル、パーセント、またはミリメートル、[MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType を参照)。


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

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


文書上に画像を配置する領域の矩形。


**Returns:**
java.awt.Rectangle
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

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Base64 からの事前定義された画像を使用して、ImageSignOptions クラスの新しいインスタンスを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | base64Content | java.lang.String | Base64 文字列形式の画像コンテンツ |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


内部リソースをクリアします


