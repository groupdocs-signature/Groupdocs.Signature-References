---
title: "ImageSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像署名の検索オプションを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

画像署名の検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | ImageSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | ドキュメントページ上の署名の画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | ドキュメントページ上の署名の画像コンテンツを取得するフラグを取得または設定します。 |
|
|  | [getMinContentSize()](#getMinContentSize--) | ゼロ以外の値の場合、このフラグは検索条件の画像の最小サイズを指定します。 |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | ゼロ以外の値の場合、このフラグは検索条件の画像の最小サイズを指定します。 |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | ゼロ以外の値の場合、このフラグは検索条件の画像の最大サイズを指定します。 |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | ゼロ以外の値の場合、このフラグは検索条件の画像の最大サイズを指定します。 |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent プロパティが有効な場合、画像署名の返却コンテンツのファイルタイプを指定します。 |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent プロパティが有効な場合、画像署名の返却コンテンツのファイルタイプを指定します。 |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


ImageSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


ドキュメントページ上の署名の画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、画像署名のコンテンツは必要な形式の生画像データを保持します。
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
デフォルトではこのオプションは無効になっています。


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


ドキュメントページ上の署名の画像コンテンツを取得するフラグを取得または設定します。
このフラグが true に設定されている場合、画像署名のコンテンツは必要な形式の生画像データを保持します。
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
デフォルトではこのオプションは無効になっています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


ゼロ以外の値の場合、このフラグは検索条件の画像の最小サイズを指定します。
デフォルトでは、このフラグは 0 に設定されており、検索結果に影響しません。


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


ゼロ以外の値の場合、このフラグは検索条件の画像の最小サイズを指定します。
デフォルトでは、このフラグは 0 に設定されており、検索結果に影響しません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


ゼロ以外の値の場合、このフラグは検索条件の画像の最大サイズを指定します。
デフォルトでは、このフラグは 0 に設定されており、検索結果に影響しません。


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


ゼロ以外の値の場合、このフラグは検索条件の画像の最大サイズを指定します。
デフォルトでは、このフラグは 0 に設定されており、検索結果に影響しません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent プロパティが有効な場合、画像署名の返却コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されています。これは、画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
ImageSignature.Format

サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、画像コンテンツは元の形式で返されます。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent プロパティが有効な場合、画像署名の返却コンテンツのファイルタイプを指定します。
デフォルトでは Null に設定されています。これは、画像コンテンツを元の形式で返すことを意味します。
この画像形式は以下で指定されます
ImageSignature.Format

サポートされる可能な値は次のとおりです: FileType.JPEG, FileType.PNG, FileType.BMP。
指定された形式がサポートされていない場合、画像コンテンツは元の形式で返されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

