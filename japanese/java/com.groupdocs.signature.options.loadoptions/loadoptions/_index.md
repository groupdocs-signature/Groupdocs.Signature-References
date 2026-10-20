---
title: "LoadOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名用にドキュメントを開く際に、パスワードなどの追加オプションを指定できます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

署名用にドキュメントを開く際に、追加オプション（パスワードなど）を指定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | 指定されたファイルタイプで LoadOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 保護されたドキュメントを開くためのパスワードを取得または設定します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 保護されたドキュメントを開くためのパスワードを取得または設定します。 |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | ドキュメントがロードされる際に、ドキュメント外部に保存されたリソースがスキップされるかどうかを示すフラグを取得または設定します。 |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | ドキュメントがロードされる際に、ドキュメント外部に保存されたリソースがスキップされるかどうかを示すフラグを取得または設定します。 |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | ロード中に読み込まれる可能性のある外部リソースのアドレスの一部を取得または設定します。 |
#getSkipExternalResources().getSkipExternalResources() が true です。
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | ロード中に読み込まれる可能性のある外部リソースのアドレスの一部を取得または設定します。 |
#getSkipExternalResources().getSkipExternalResources() が true です。
|
|  | [getPermissions()](#getPermissions--) | 印刷、変更、データ抽出などの PDF ドキュメント権限です。 |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | 内部セッターで、ドキュメント読み込みプロセッサーがファイルから解析された権限を記録するために使用されます。 |
|
|  | [getFileType()](#getFileType--) | ドキュメントのファイルタイプを取得します。 |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | ドキュメントのファイルタイプを設定し、ドキュメントの内容から自動検出されないようにします。 |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions クラスの新しいインスタンスを初期化します。


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


指定されたファイルタイプで LoadOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | ドキュメントのファイルタイプです。#setFileType(FileType).setFileType(FileType) を参照してください。 |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


保護されたドキュメントを開くためのパスワードを取得または設定します。
署名済みドキュメントを保護された状態で保存する際にも使用されます。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


保護されたドキュメントを開くためのパスワードを取得または設定します。
署名済みドキュメントを保護された状態で保存する際にも使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


ドキュメントがロードされる際に、ドキュメント外部に保存されたリソースがスキップされるかどうかを示すフラグを取得または設定します。
デフォルト値は true です。


ドキュメントは外部リソースを参照できます：ワードプロセッシングにおけるリンク画像や INCLUDEPICTURE フィールド
ドキュメント、プレゼンテーションやスプレッドシートのリンク画像、SVG 画像が参照する画像やスタイルシート
このようなリソースをロードすることは、ドキュメントに記載されたアドレスにリクエストを送ることを意味します。処理するサーバー上では
他者のドキュメントを処理する際、サーバー側リクエストフォージェリのリスクがあり、オフライン環境では
リクエストが失敗するか、タイムアウトを待ちます。


true の場合、外部リソースはロードされませんが、アドレスに以下のいずれかが含まれるものは除外されます
#getWhitelistedResources().getWhitelistedResources(). スキップされたリソースはページプレビューや、として保存されたドキュメント内で描画されません
画像やイメージ、バーコードおよびQRコードの検索ではそれらが検出されません。埋め込み画像は影響を受けず、そして
ハイパーリンクは決してたどられません。この設定はアーカイブ内のドキュメントにも適用されます。


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


ドキュメントがロードされる際に、ドキュメント外部に保存されたリソースがスキップされるかどうかを示すフラグを取得または設定します。
デフォルト値は true です。#getSkipExternalResources().getSkipExternalResources() を参照してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


ロード中に読み込まれる可能性のある外部リソースのアドレスの一部を取得または設定します。
#getSkipExternalResources().getSkipExternalResources() は true です。アドレスはそれらのいずれかを含む場合（大文字小文字を区別せず）にロードされます。
空の値は無視されます。デフォルトは空のリストです。null を設定するとクリアされます。


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


ロード中に読み込まれる可能性のある外部リソースのアドレスの一部を取得または設定します。
#getSkipExternalResources().getSkipExternalResources() は true です。#getWhitelistedResources().getWhitelistedResources() を参照してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


印刷、変更、データ抽出などの PDF ドキュメント権限です。
PDF ドキュメント専用です。読み取り専用 \\u2014 ドキュメントの読み込み時に自動的に設定されます。
この値は [Permissions](../../com.groupdocs.signature.options/permissions) からのフラグの組み合わせです。


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


内部セッターで、ドキュメント読み込みプロセッサーがファイルから解析された権限を記録するために使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


ドキュメントのファイルタイプを取得します。それが [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown)（デフォルト）の場合、
ファイルタイプはドキュメントの内容から検出されます。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


ドキュメントのファイルタイプを設定し、ドキュメントの内容から自動検出されないようにします。
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

