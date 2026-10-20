---
title: "BarcodeSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "バーコード署名オプションを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

バーコード署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | デフォルト値で BarcodeSignOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | バーコードのタイプを取得または設定します。 |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | バーコードのタイプを取得または設定します。 |
|
|  | [getForeColor()](#getForeColor--) | バーコードバーの前景色を取得または設定します |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | バーコードバーの前景色を取得または設定します |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | バーコードバーの前景色を取得または設定します |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [getInnerMargins()](#getInnerMargins--) | バーコード要素と結果画像の境界間のスペースを取得または設定します。 |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | バーコード要素と結果画像の境界間のスペースを取得または設定します。 |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | 結果のバーコード画像内のテキストの配置を取得または設定します。 |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 結果のバーコード画像内のテキストの配置を取得または設定します。 |
|
|  | [getReturnContent()](#getReturnContent--) | ドキュメントページに配置された署名のバーコード画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | ドキュメントページに配置された署名のバーコード画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。 |
|
|  | [validate()](#validate--) | バーコードオプションパラメータを検証する内部メソッドです。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


デフォルト値で BarcodeSignOptions クラスの新しいインスタンスを初期化します。


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | バーコードテキスト |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | バーコードテキスト |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | バーコードエンコードタイプは [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) を参照してください |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


バーコードのタイプを取得または設定します。


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


バーコードのタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


バーコードバーの前景色を取得または設定します
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


バーコードバーの前景色を取得または設定します
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


バーコードバーの前景色を取得または設定します
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


バーコード要素と結果画像の境界間のスペースを取得または設定します。


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


バーコード要素と結果画像の境界間のスペースを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


結果のバーコード画像内のテキストの配置を取得または設定します。
デフォルト値は None です。


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


結果のバーコード画像内のテキストの配置を取得または設定します。
デフォルト値は None です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


ドキュメントページに配置された署名のバーコード画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、バーコード署名画像のコンテンツは必要な形式で生の画像データを保持します
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
デフォルトではこのオプションは無効になっています。


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


ドキュメントページに配置された署名のバーコード画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、バーコード署名画像のコンテンツは必要な形式で生の画像データを保持します
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
デフォルトではこのオプションは無効になっています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されています。これは、バーコード画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、バーコード画像コンテンツは .png 形式で返されます。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されています。これは、バーコード画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、バーコード画像コンテンツは .png 形式で返されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


バーコードオプションパラメータを検証する内部メソッドです。


### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
