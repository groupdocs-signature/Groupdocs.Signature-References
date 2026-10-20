---
title: "PresentationSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "プレゼンテーション ドキュメントの保存オプション。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

プレゼンテーション ドキュメントの保存オプション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | PresentationSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | PresentationSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。 |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | PresentationSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。 |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | PresentationSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。 |
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
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


PresentationSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


PresentationSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat)。 |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


PresentationSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 同じファイルで署名済みファイルを上書きするかどうかのフラグです。 |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PresentationSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat)。 |
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
