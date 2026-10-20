---
title: "JpegSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像ドキュメント用の JPEG 保存オプションです。"
type: docs
weight: 19
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

画像ドキュメント用の JPEG 保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | JpegSaveOptions をデフォルト値で作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | ロスレス jpeg 画像のチャンネルあたりビット数を取得または設定します。 |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | ロスレス jpeg 画像のチャンネルあたりビット数を取得または設定します。 |
|
|  | [getColorType()](#getColorType--) | jpeg 画像のカラータイプを取得または設定します。 |
|
|  | [setColorType(int value)](#setColorType-int-) | jpeg 画像のカラータイプを取得または設定します。 |
|
|  | [getComment()](#getComment--) | jpeg ファイルのコメントを取得または設定します。 |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | jpeg ファイルのコメントを取得または設定します。 |
|
|  | [getCompressionType()](#getCompressionType--) | 圧縮タイプを取得または設定します。 |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | 圧縮タイプを取得または設定します。 |
|
|  | [getQuality()](#getQuality--) | 画像品質を取得または設定します。 |
|
|  | [setQuality(int value)](#setQuality-int-) | 画像品質を取得または設定します。 |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | 8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。 |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。 |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


JpegSaveOptions をデフォルト値で作成します。


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


ロスレス jpeg 画像のチャンネルあたりビット数を取得または設定します。
現在、チャネルあたり2ビットから8ビットまでサポートしています。


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


ロスレス jpeg 画像のチャンネルあたりビット数を取得または設定します。
現在、チャネルあたり2ビットから8ビットまでサポートしています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg 画像のカラータイプを取得または設定します。


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg 画像のカラータイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


jpeg ファイルのコメントを取得または設定します。


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg ファイルのコメントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


圧縮タイプを取得または設定します。


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


圧縮タイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


画像品質を取得または設定します。


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


画像品質を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8 ビット値を n ビット値に合わせるサンプル丸めモードを取得または設定します。
JpegOptions.BitsPerChannel.


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


署名済みドキュメントのファイル形式を取得または設定します。このオプション クラスでは使用されていないため非表示です。


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


署名済みドキュメントのファイル形式を取得または設定します。このオプション クラスでは使用されていないため非表示です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

