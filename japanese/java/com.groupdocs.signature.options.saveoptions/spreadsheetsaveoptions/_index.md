---
title: "SpreadsheetSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スプレッドシート ドキュメントの保存オプション。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

スプレッドシート ドキュメントの保存オプション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | SpreadsheetSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | SpreadsheetSaveOptions クラスの新しいインスタンスを事前定義された出力ファイル形式で初期化します。 |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | SpreadsheetSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


SpreadsheetSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


SpreadsheetSaveOptions クラスの新しいインスタンスを事前定義された出力ファイル形式で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイル形式を指定します。 |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


SpreadsheetSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイル形式を指定します。 |
|
|  | overwriteExistingFile | boolean | 同じファイルで署名済みファイルを上書きするかどうかのフラグです。 |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


署名されたドキュメントのファイル形式を取得または設定します。


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


署名されたドキュメントのファイル形式を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
