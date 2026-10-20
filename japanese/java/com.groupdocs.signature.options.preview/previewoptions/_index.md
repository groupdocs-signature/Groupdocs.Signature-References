---
title: "PreviewOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントプレビューオプションを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

ドキュメントプレビューオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | PreviewOptions オブジェクトを初期化します。 |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | PreviewOptions オブジェクトを初期化します。 |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | PreviewOptions オブジェクトを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getWidth()](#getWidth--) | プレビュー画像の幅を取得または設定します。 |
|
|  | [setWidth(int value)](#setWidth-int-) | プレビュー画像の幅を取得または設定します。 |
|
|  | [getHeight()](#getHeight--) | プレビュー画像の高さを取得または設定します。 |
|
|  | [setHeight(int value)](#setHeight-int-) | プレビュー画像の高さを取得または設定します。 |
|
|  | [getPageNumbers()](#getPageNumbers--) | プレビュー画像のページ番号を取得または設定します。 |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | プレビュー画像のページ番号を取得または設定します。 |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | プレビュー画像の形式を取得または設定します。 |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | プレビュー画像の形式を取得または設定します。 |
|
|  | [getHideSignatures()](#getHideSignatures--) | ページプレビュー画像から署名を非表示にするフラグを取得または設定します。 |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | ページプレビュー画像から署名を非表示にするフラグを取得または設定します。 |
|
|  | [getResolution()](#getResolution--) | プレビュー画像の解像度を DPI（ドット毎インチ）で取得します。 |
|
|  | [setResolution(int value)](#setResolution-int-) | プレビュー画像の解像度を DPI（ドット毎インチ）で設定します。 |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


PreviewOptions オブジェクトを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | 出力ページプレビュー ストリームを作成するメソッドを定義するインターフェイス。 |
|
|  | pageNumbers | int[] | 希望するページ番号 |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


PreviewOptions オブジェクトを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | 出力ページプレビュー ストリームを作成するメソッドを定義するインターフェイス。 |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


PreviewOptions オブジェクトを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 出力ファイルへのパス。 |
|
|  | pageNumbers | int[] | 希望するページ番号 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


プレビュー画像の幅を取得または設定します。


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


プレビュー画像の幅を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


プレビュー画像の高さを取得または設定します。


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


プレビュー画像の高さを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


プレビュー画像のページ番号を取得または設定します。


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


プレビュー画像のページ番号を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


プレビュー画像の形式を取得または設定します。


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


プレビュー画像の形式を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


ページプレビュー画像から署名を非表示にするフラグを取得または設定します。
IsSignature とマークされた署名のみが、生成された文書ページ画像から非表示になります。


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


ページプレビュー画像から署名を非表示にするフラグを取得または設定します。
IsSignature とマークされた署名のみが、生成された文書ページ画像から非表示になります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


プレビュー画像の解像度を DPI（ドット毎インチ）で取得します。


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


プレビュー画像の解像度を DPI（ドット毎インチ）で設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

