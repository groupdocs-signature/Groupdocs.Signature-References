---
title: "SaveOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名用にドキュメントを保存する際に、パスワードなどの追加オプションを指定できます。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

署名用にドキュメントを保存する際に、追加オプション（パスワードなど）を指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | デフォルト値で SaveOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | 指定された出力タイプと上書きフラグを使用して SaveOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | 既存のファイルを新しい出力ファイルで上書きするかどうかを取得または設定します。 |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | 既存のファイルを新しい出力ファイルで上書きするかどうかを取得または設定します。 |
|
|  | [getPassword()](#getPassword--) | パスワード保護付きで署名済みドキュメントを保存するためのパスワードを取得または設定します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | パスワード保護付きで署名済みドキュメントを保存するためのパスワードを取得または設定します。 |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | LoadOptions からのパスワードを使用して署名済みドキュメントを保護された状態で保存するかどうかを取得または設定します。 |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | LoadOptions からのパスワードを使用して署名済みドキュメントを保護された状態で保存するかどうかを取得または設定します。 |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | 出力ファイルパスに拡張子がない場合に自動的に拡張子を追加するかどうかのフラグを取得または設定します。 |
既定値は false です。
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | 出力ファイルパスに拡張子がない場合に自動的に拡張子を追加するかどうかのフラグを取得または設定します。 |
既定値は false です。
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


デフォルト値で SaveOptions クラスの新しいインスタンスを初期化します。


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


指定された出力タイプと上書きフラグを使用して SaveOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 同じファイルで署名済みファイルを上書きするかどうかのフラグです。 |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


既存のファイルを新しい出力ファイルで上書きするかどうかを取得または設定します。
それ以外の場合は、番号をサフィックスとして新しいファイルが作成されます。


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


既存のファイルを新しい出力ファイルで上書きするかどうかを取得または設定します。
それ以外の場合は、番号をサフィックスとして新しいファイルが作成されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


パスワード保護付きで署名済みドキュメントを保存するためのパスワードを取得または設定します。
このプロパティは Image ドキュメントではサポートされていません。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


パスワード保護付きで署名済みドキュメントを保存するためのパスワードを取得または設定します。
このプロパティは Image ドキュメントではサポートされていません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


LoadOptions からのパスワードを使用して署名済みドキュメントを保護された状態で保存するかどうかを取得または設定します。
既定値は true です。
このプロパティは Image ドキュメントではサポートされていません。


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


LoadOptions からのパスワードを使用して署名済みドキュメントを保護された状態で保存するかどうかを取得または設定します。
既定値は true です。
このプロパティは Image ドキュメントではサポートされていません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


出力ファイルパスに拡張子がない場合に自動的に拡張子を追加するかどうかのフラグを取得または設定します。
既定値は false です。


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


出力ファイルパスに拡張子がない場合に自動的に拡張子を追加するかどうかのフラグを取得または設定します。
既定値は false です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

