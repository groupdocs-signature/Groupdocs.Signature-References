---
title: "WordProcessingSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "WordProcessing ドキュメントの保存オプション。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

WordProcessing ドキュメントの保存オプション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | WordProcessingSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。 |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。 |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | 署名されたドキュメントのオプションのOOXML準拠レベルです。 |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | 署名されたドキュメントのオプションのOOXML準拠レベルです。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライド |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


WordProcessingSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat)。 |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力タイプと上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 同じファイルで署名済みファイルを上書きするかどうかのフラグです。 |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


WordProcessingSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat)。 |
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

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


署名されたドキュメントのオプションのOOXML準拠レベルです。設定すると、
元のドキュメントの準拠設定です。このとき
null
(デフォルト)、ロードされたドキュメントの
準拠は保持されます。OOXML形式に対してのみ適用されます
(Docx、Docm、Dotx、Dotm、FlatOpc および FlatOpc バリアント)。


この値は [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) のいずれかです。


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


署名されたドキュメントのオプションのOOXML準拠レベルです。設定すると、
元のドキュメントの準拠設定です。このとき
null
(デフォルト)、ロードされたドキュメントの
準拠は保持されます。OOXML形式に対してのみ適用されます
(Docx、Docm、Dotx、Dotm、FlatOpc および FlatOpc バリアント)。


この値は [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) のいずれかです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライド


**Returns:**
java.lang.String -
