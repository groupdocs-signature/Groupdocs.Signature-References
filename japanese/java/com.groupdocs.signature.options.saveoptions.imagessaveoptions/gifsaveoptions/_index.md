---
title: "GifSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像ドキュメント用の GIF 形式保存オプションです。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

画像ドキュメント用の GIF 形式保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | デフォルト値で GifSaveOptions を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF の背景色インデックスを取得または設定します。 |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF の背景色インデックスを取得または設定します。 |
|
|  | [getColorResolution()](#getColorResolution--) | GIF の色解像度を取得または設定します。 |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | GIF の色解像度を取得または設定します。 |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | パレット補正が適用されるかどうかを示す値を取得または設定します。 |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | パレット補正が適用されるかどうかを示す値を取得または設定します。 |
|
|  | [hasTrailer()](#hasTrailer--) | GIF にトレーラーがあるかどうかを示す値を取得または設定します。 |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | GIF にトレーラーがあるかどうかを示す値を取得または設定します。 |
|
|  | [getInterlaced()](#getInterlaced--) | 画像をインターレースする場合は true。 |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | 画像をインターレースする場合は true。 |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | パレットエントリがソートされているかどうかを示す値を取得または設定します。 |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | パレットエントリがソートされているかどうかを示す値を取得または設定します。 |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF のピクセルアスペクト比を取得または設定します。 |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF のピクセルアスペクト比を取得または設定します。 |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


デフォルト値で GifSaveOptions を作成します。


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF の背景色インデックスを取得または設定します。


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF の背景色インデックスを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF の色解像度を取得または設定します。

<br />

*** ** * ** ***

カラー解像度 - 元画像で利用可能な各プライマリカラーあたりのビット数から 1 を引いた値です。この値は、グラフィックで選択された色が抽出された全パレットのサイズを表し、実際にグラフィックで使用された色の数ではありません。例えば、このフィールドの値が 3 の場合、元画像のパレットは画像作成に利用できる各プライマリカラーあたり 4 ビットを持っていました。この値は、ソースマシンで全パレットのすべての色が利用できなくても、元パレットの豊かさを示すために設定すべきです。

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF の色解像度を取得または設定します。

<br />

*** ** * ** ***

カラー解像度 - 元画像で利用可能な各プライマリカラーあたりのビット数から 1 を引いた値です。この値は、グラフィックで選択された色が抽出された全パレットのサイズを表し、実際にグラフィックで使用された色の数ではありません。例えば、このフィールドの値が 3 の場合、元画像のパレットは画像作成に利用できる各プライマリカラーあたり 4 ビットを持っていました。この値は、ソースマシンで全パレットのすべての色が利用できなくても、元パレットの豊かさを示すために設定すべきです。

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


パレット補正が適用されるかどうかを示す値を取得または設定します。

<br />

*** ** * ** ***

パレット補正とは、画像が GIF にエクスポートされるたびに、ソース画像の色が解析され、最適なパレットが構築されることを意味します（画像のパレットが存在しない、またはオプションで指定されていない場合）。解析プロセスには時間がかかりますが、出力画像は最適なカラーパレットを持ち、視覚的により良い結果になります。

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


パレット補正が適用されるかどうかを示す値を取得または設定します。

<br />

*** ** * ** ***

パレット補正とは、画像が GIF にエクスポートされるたびに、ソース画像の色が解析され、最適なパレットが構築されることを意味します（画像のパレットが存在しない、またはオプションで指定されていない場合）。解析プロセスには時間がかかりますが、出力画像は最適なカラーパレットを持ち、視覚的により良い結果になります。

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF にトレーラーがあるかどうかを示す値を取得または設定します。


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF にトレーラーがあるかどうかを示す値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


画像をインターレースする場合は true。


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


画像をインターレースする場合は true。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


パレットエントリがソートされているかどうかを示す値を取得または設定します。


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


パレットエントリがソートされているかどうかを示す値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF のピクセルアスペクト比を取得または設定します。

<br />

*** ** * ** ***

ピクセルアスペクト比 - 元画像のピクセルのアスペクト比の近似値を計算するために使用される係数です。フィールドの値が 0 でない場合、このアスペクト比の近似は次の式に基づいて計算されます: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 ピクセルアスペクト比は、ピクセルの幅を高さで割った商として定義されます。このフィールドの値範囲は、最も幅の広いピクセル 4:1 から最も高さの高いピクセル 1:4 までを 1/64 単位で指定できます。値: 0 - アスペクト比情報が提供されていません。1..255 - 計算に使用される値。

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF のピクセルアスペクト比を取得または設定します。

<br />

*** ** * ** ***

ピクセルアスペクト比 - 元画像のピクセルのアスペクト比の近似値を計算するために使用される係数です。フィールドの値が 0 でない場合、このアスペクト比の近似は次の式に基づいて計算されます: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64 ピクセルアスペクト比は、ピクセルの幅を高さで割った商として定義されます。このフィールドの値範囲は、最も幅の広いピクセル 4:1 から最も高さの高いピクセル 1:4 までを 1/64 単位で指定できます。値: 0 - アスペクト比情報が提供されていません。1..255 - 計算に使用される値。

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

