---
title: "ExportImageSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントを画像にエクスポートするための保存オプション。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

ドキュメントを画像にエクスポートするための保存オプション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | 既定値で ExportAsImageSaveOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | 指定されたファイル形式で ExportAsImageSaveOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | エクスポート対象のドキュメントページ番号を取得または設定します。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | エクスポート対象のドキュメントページ番号を取得または設定します。 |
|
|  | [getExportAllPages()](#getExportAllPages--) | 各ページをエクスポートするかどうかのフラグです。 |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | 各ページをエクスポートするかどうかのフラグです。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 署名対象ページを指定するオプションです。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 署名対象ページを指定するオプションです。 |
|
|  | [getPageColumns()](#getPageColumns--) | エクスポートされた画像の列数を取得または設定します。 |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | エクスポートされた画像の列数を取得または設定します。 |
|
|  | [getBorder()](#getBorder--) | 画像の境界設定を取得または設定します。 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 画像の境界設定を取得または設定します。 |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | Tiff 画像内でドキュメントページを別々のフレームに配置します。 |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | Tiff 画像内でドキュメントページを別々のフレームに配置します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


既定値で ExportAsImageSaveOptions クラスの新しいインスタンスを初期化します。


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


指定されたファイル形式で ExportAsImageSaveOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力画像のファイル形式です。 |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


エクスポート対象のドキュメントページ番号を取得または設定します。
最小値は 1 です。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


エクスポート対象のドキュメントページ番号を取得または設定します。
最小値は 1 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


各ページをエクスポートするかどうかのフラグです。


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


各ページをエクスポートするかどうかのフラグです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


署名対象ページを指定するオプションです。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


署名対象ページを指定するオプションです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


エクスポートされた画像の列数を取得または設定します。
画像を横に並べる必要がある場合はこのプロパティを使用します。


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


エクスポートされた画像の列数を取得または設定します。
画像を横に並べる必要がある場合はこのプロパティを使用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


画像の境界設定を取得または設定します。デフォルトではこの値は設定されていません。


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


画像の境界設定を取得または設定します。デフォルトではこの値は設定されていません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


Tiff 画像内でドキュメントページを別々のフレームに配置します。


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


Tiff 画像内でドキュメントページを別々のフレームに配置します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
