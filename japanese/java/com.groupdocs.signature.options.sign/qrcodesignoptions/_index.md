---
title: "QrCodeSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "QRコード署名オプションを表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

QRコード署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | QRCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | QRCodeSignOptions クラスの新しいインスタンスをテキストで初期化します。 |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QRCode のタイプを取得または設定します。 |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCode のタイプを取得または設定します。 |
|
|  | [getForeColor()](#getForeColor--) | QR-Code バーの前景色を取得または設定します。 |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | QR-Code バーの前景色を取得または設定します。 |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | QR-Code バーの前景色を取得または設定します。 |
このプロパティの使用は検証時に問題を引き起こす可能性があります。
|
|  | [getInnerMargins()](#getInnerMargins--) | QRCode 要素と結果画像の境界間のスペースを取得または設定します。 |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | QRCode 要素と結果画像の境界間のスペースを取得または設定します。 |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | 結果の QR-code 画像内のテキストの配置を取得または設定します。 |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 結果の QR-code 画像内のテキストの配置を取得または設定します。 |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | QRコードロゴ画像のファイル名を取得または設定します。 |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | QRコードロゴ画像のファイル名を取得または設定します。 |
|
|  | [getLogoStream()](#getLogoStream--) | QRコードロゴ画像のストリームを取得または設定します。 |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | QRコードロゴ画像のストリームを取得または設定します。 |
|
|  | [getData()](#getData--) | QRコードコンテンツにシリアライズするカスタムオブジェクトを取得または設定します。 |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | QRコードコンテンツにシリアライズするカスタムオブジェクトを取得または設定します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [getReturnContent()](#getReturnContent--) | ドキュメントページに配置された署名の QRコード画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | ドキュメントページに配置された署名の QRコード画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


QRCodeSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


QRCodeSignOptions クラスの新しいインスタンスをテキストで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 署名テキスト。 |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


テキストを使用して BarcodeSignOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | QRコードテキスト |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRコードエンコードタイプは [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) を参照してください。 |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRCode のタイプを取得または設定します。


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRCode のタイプを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


QR-Code バーの前景色を取得または設定します。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


QR-Code バーの前景色を取得または設定します。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


QR-Code バーの前景色を取得または設定します。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


QRCode 要素と結果画像の境界間のスペースを取得または設定します。


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


QRCode 要素と結果画像の境界間のスペースを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


結果の QR-code 画像内のテキストの配置を取得または設定します。
デフォルト値は None です。


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


結果の QR-code 画像内のテキストの配置を取得または設定します。
デフォルト値は None です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


QRコードロゴ画像のファイル名を取得または設定します。
このプロパティは LogoStream が指定されていない場合にのみ使用されます。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


QRコードロゴ画像のファイル名を取得または設定します。
このプロパティは LogoStream が指定されていない場合にのみ使用されます。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


QRコードロゴ画像のストリームを取得または設定します。
このプロパティが指定されている場合、常に LogoGuid の代わりに使用されます。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


QRコードロゴ画像のストリームを取得または設定します。
このプロパティが指定されている場合、常に LogoGuid の代わりに使用されます。
このプロパティの使用は検証に問題を引き起こす可能性があります。注意して使用してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


QRコードコンテンツにシリアライズするカスタムオブジェクトを取得または設定します。


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


QRコードコンテンツにシリアライズするカスタムオブジェクトを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


ドキュメントページに配置された署名の QRコード画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、QRコード署名画像コンテンツは必要な形式の生画像データを保持します。
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
デフォルトではこのオプションは無効になっています。


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


ドキュメントページに配置された署名の QRコード画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、QRコード署名画像コンテンツは必要な形式の生画像データを保持します。
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


ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されます。これは、QRコード画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、QRコード画像コンテンツは .png 形式で返されます。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されます。これは、QRコード画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
QrCodeSignature.Format
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、QRコード画像コンテンツは .png 形式で返されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
