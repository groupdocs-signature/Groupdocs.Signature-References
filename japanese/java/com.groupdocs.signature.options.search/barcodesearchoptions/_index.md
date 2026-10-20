---
title: "BarcodeSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "バーコード署名の抽象検索オプションを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

バーコード署名の抽象検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | SearchBarcodeOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | SearchBarcodeOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。 |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | SearchBarcodeOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | バーコードを検索するために Encode Type プロパティを指定します。 |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | バーコードを検索するために Encode Type プロパティを指定します。 |
|
|  | [getText()](#getText--) | 検索および一致させる場合の Barcode 署名テキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 検索および一致させる場合の Barcode 署名テキストを指定します。 |
|
|  | [getMatchType()](#getMatchType--) | Barcode テキストマッチタイプ検索を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Barcode テキストマッチタイプ検索を取得または設定します。 |
|
|  | [getReturnContent()](#getReturnContent--) | ドキュメントページ上の署名の Barcode 画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | ドキュメントページ上の署名の Barcode 画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent プロパティが有効な場合に、バーコード署名の返却画像コンテンツのファイルタイプを指定します。 |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


SearchBarcodeOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


SearchBarcodeOptions クラスの新しいインスタンスをエンコードタイプの値で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode エンコードタイプを指定します。 |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


SearchBarcodeOptions クラスの新しいインスタンスをエンコードタイプとテキストの値で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode エンコードタイプを指定します。 |
|
|  | テキスト | java.lang.String | Barcode 署名のテキストを設定します。 |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


バーコードを検索するために Encode Type プロパティを指定します。
この値が設定されていない場合、サポートされているすべての Barcode タイプに対して検索が実行されます。


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


バーコードを検索するために Encode Type プロパティを指定します。
この値が設定されていない場合、サポートされているすべての Barcode タイプに対して検索が実行されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


検索および一致させる場合の Barcode 署名テキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


検索および一致させる場合の Barcode 署名テキストを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Barcode テキストのマッチタイプ検索を取得または設定します。Text プロパティが設定されている場合にのみ使用されます。


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Barcode テキストのマッチタイプ検索を取得または設定します。Text プロパティが設定されている場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


ドキュメントページ上の署名の Barcode 画像コンテンツを取得するフラグを取得または設定します。
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


ドキュメントページ上の署名の Barcode 画像コンテンツを取得するフラグを取得または設定します。
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、バーコード画像コンテンツは .png 形式で返されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

