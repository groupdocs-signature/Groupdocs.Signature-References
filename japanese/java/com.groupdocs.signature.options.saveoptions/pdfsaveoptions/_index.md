---
title: "PdfSaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDF ドキュメントの保存オプション。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF ドキュメントの保存オプション。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | PdfSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | PdfSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。 |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | PdfSaveOptions クラスの新しいインスタンスを上書きフラグ付きで初期化します。 |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | PdfSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 署名されたドキュメントのファイル形式を取得または設定します。 |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | 権限パスワード（プライマリパスワード）は、権限設定を変更するためにパスワードが必要です。 |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 権限パスワード（プライマリパスワード）は、権限設定を変更するためにパスワードが必要です。 |
|
|  | [getPermissions()](#getPermissions--) | 印刷、変更、データ抽出などの PDF ドキュメント権限です。 |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | 印刷、変更、データ抽出などの PDF ドキュメント権限です。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


PdfSaveOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


PdfSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)。 |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


PdfSaveOptions クラスの新しいインスタンスを上書きフラグ付きで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 同じファイルで署名済みファイルを上書きするかどうかのフラグです。 |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PdfSaveOptions クラスの新しいインスタンスを指定された出力ファイル形式と上書きフラグで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileFormat | int | 出力ファイルタイプ [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat)。 |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


権限パスワード（プライマリパスワード）は、権限設定を変更するためにパスワードが必要です。


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


権限パスワード（プライマリパスワード）は、権限設定を変更するためにパスワードが必要です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


印刷、変更、データ抽出などの PDF ドキュメント権限です。


これらの権限を変更するには、
PermissionsPassword
設定する必要があります。
この値は [Permissions](../../com.groupdocs.signature.options/permissions) からのフラグの組み合わせです。
A
null
この値は明示的な権限が適用されていないことを意味します。


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


印刷、変更、データ抽出などの PDF ドキュメント権限です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
