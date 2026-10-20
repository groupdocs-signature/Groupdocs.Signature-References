---
title: "QrCodeSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "QRコード署名の抽象検索オプションを表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

QRコード署名の抽象検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | QRCodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。 |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QRコードを検索するために Encode Type プロパティを指定します。 |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRコードを検索するために Encode Type プロパティを指定します。 |
|
|  | [getText()](#getText--) | 検索および一致させる場合の QR-Code 署名テキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 検索および一致させる場合の QR-Code 署名テキストを指定します。 |
|
|  | [getMatchType()](#getMatchType--) | QR-Code テキストマッチタイプ検索を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | QR-Code テキストマッチタイプ検索を取得または設定します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [getReturnContent()](#getReturnContent--) | ドキュメントページ上の署名の QR-Code 画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | ドキュメントページ上の署名の QR-Code 画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent プロパティが有効な場合に返される QRコード署名の画像コンテンツのファイルタイプを指定します。 |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


QRCodeSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code エンコードタイプを指定します。 |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


QRCodeSearchOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code エンコードタイプを指定します。 |
|
|  | テキスト | java.lang.String | QR-Code 署名のテキストを設定します。 |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRコードを検索するために Encode Type プロパティを指定します。
この値が設定されていない場合、サポートされているすべての QR-Code タイプに対して検索が実行されます。


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRコードを検索するために Encode Type プロパティを指定します。
この値が設定されていない場合、サポートされているすべての QR-Code タイプに対して検索が実行されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


検索および一致させる場合の QR-Code 署名テキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


検索および一致させる場合の QR-Code 署名テキストを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


QR-Code テキストマッチタイプ検索を取得または設定します。これは Text プロパティが設定されている場合にのみ使用されます。


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


QR-Code テキストマッチタイプ検索を取得または設定します。これは Text プロパティが設定されている場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

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


ドキュメントページ上の署名の QR-Code 画像コンテンツを取得するフラグを取得または設定します。
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


ドキュメントページ上の署名の QR-Code 画像コンテンツを取得するフラグを取得または設定します。
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
()
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、元の .png の QR-Code 画像コンテンツが返されます。


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
()
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、元の .png の QR-Code 画像コンテンツが返されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

