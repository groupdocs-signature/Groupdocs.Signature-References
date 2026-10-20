---
title: "BmpSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像ドキュメント用の BMP 保存オプションです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

画像ドキュメント用の BMP 保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | デフォルト値で BmpSaveOptions を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | 画像のピクセルあたりビット数を取得または設定します。 |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 画像のピクセルあたりビット数を取得または設定します。 |
|
|  | [getCompression()](#getCompression--) | 圧縮を取得または設定します。 |
|
|  | [setCompression(int value)](#setCompression-int-) | 圧縮を取得または設定します。 |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 水平解像度を取得または設定します。 |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 水平解像度を取得または設定します。 |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 垂直解像度を取得または設定します。 |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | 垂直解像度を取得または設定します。 |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


デフォルト値で BmpSaveOptions を作成します。


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


画像のピクセルあたりビット数を取得または設定します。


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


画像のピクセルあたりビット数を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


圧縮を取得または設定します。参照: [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)。


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


圧縮を取得または設定します。参照: [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


水平解像度を取得または設定します。注: 丸め処理のため、結果の
解像度は指定した値とわずかに異なる場合があります。


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


水平解像度を取得または設定します。注: 丸め処理のため、結果の
解像度は指定した値とわずかに異なる場合があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


垂直解像度を取得または設定します。注: 丸め処理のため、結果の
解像度は指定した値とわずかに異なる場合があります。


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


垂直解像度を取得または設定します。注: 丸め処理のため、結果の
解像度は指定した値とわずかに異なる場合があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

