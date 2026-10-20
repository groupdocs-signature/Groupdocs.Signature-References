---
title: "PngSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像ドキュメント用の PNG 保存オプションです。"
type: docs
weight: 22
url: /ja/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

画像ドキュメント用の PNG 保存オプションです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | PngSaveOptions をデフォルト値で作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | ビット深度です。 |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | ビット深度です。 |
|
|  | [getColorType()](#getColorType--) | 取得または設定するタイプ |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | 取得または設定するタイプ |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | png 画像の圧縮レベル（0〜9 の範囲）、9 が最大圧縮です。 |
0 は保存モードです。
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | png 画像の圧縮レベル（0〜9 の範囲）、9 が最大圧縮です。 |
0 は保存モードです。
|
|  | [getFilterType()](#getFilterType--) | 取得または設定するフィルタタイプ |
PngFilterType
png ファイルの保存プロセス中に使用されます。
|
|  | [setFilterType(int value)](#setFilterType-int-) | 取得または設定するフィルタタイプ |
PngFilterType
png ファイルの保存プロセス中に使用されます。
|
|  | [getProgressive()](#getProgressive--) | この PngSaveOptions がプログレッシブかどうかを示す値を取得または設定します。 |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | この PngSaveOptions がプログレッシブかどうかを示す値を取得または設定します。 |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


PngSaveOptions をデフォルト値で作成します。


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


ビット深度です。


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


ビット深度です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


取得または設定するタイプ
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


取得または設定するタイプ
PngColorType
.


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png 画像の圧縮レベル（0〜9 の範囲）、9 が最大圧縮です。
0 は保存モードです。


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png 画像の圧縮レベル（0〜9 の範囲）、9 が最大圧縮です。
0 は保存モードです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


取得または設定するフィルタタイプ
PngFilterType
png ファイルの保存プロセス中に使用されます。


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


取得または設定するフィルタタイプ
PngFilterType
png ファイルの保存プロセス中に使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


この PngSaveOptions がプログレッシブかどうかを示す値を取得または設定します。


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


この PngSaveOptions がプログレッシブかどうかを示す値を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

