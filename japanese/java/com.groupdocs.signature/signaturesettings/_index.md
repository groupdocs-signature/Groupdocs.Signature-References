---
title: "SignatureSettings"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "動作をカスタマイズするための設定を定義します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature/signaturesettings/
---
**Inheritance:**
java.lang.Object
```
public class SignatureSettings
```

[Signature](../../com.groupdocs.signature/signature) の動作をカスタマイズするための設定を定義します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SignatureSettings()](#SignatureSettings--) | デフォルト値を持つデフォルトの SignatureSettings インスタンスを作成します。 |
|
|  | [SignatureSettings(ILogger logger)](#SignatureSettings-com.groupdocs.signature.logging.ILogger-) | Logger 実装を使用したデフォルトの SignatureSettings インスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getDefaultCulture()](#getDefaultCulture--) | ドキュメント処理中に使用されるデフォルトのカルチャを取得または設定します。 |
|
|  | [setDefaultCulture(Locale value)](#setDefaultCulture-java.util.Locale-) | ドキュメント処理中に使用されるデフォルトのカルチャを取得または設定します。 |
|
|  | [getShowDeletedSiganturesInfo()](#getShowDeletedSiganturesInfo--) | 削除された署名を Document Info の結果に含めるフラグを取得または設定します。 |
|
|  | [setShowDeletedSiganturesInfo(boolean value)](#setShowDeletedSiganturesInfo-boolean-) | 削除された署名を Document Info の結果に含めるフラグを取得または設定します。 |
|
|  | [getSaveDocumentOnEmptyUpdate()](#getSaveDocumentOnEmptyUpdate--) | Update メソッドに更新する署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。 |
|
|  | [setSaveDocumentOnEmptyUpdate(boolean value)](#setSaveDocumentOnEmptyUpdate-boolean-) | Update メソッドに更新する署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。 |
|
|  | [getSaveDocumentOnEmptyDelete()](#getSaveDocumentOnEmptyDelete--) | Delete メソッドに削除対象の署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。 |
|
|  | [setSaveDocumentOnEmptyDelete(boolean value)](#setSaveDocumentOnEmptyDelete-boolean-) | Delete メソッドに削除対象の署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。 |
|
|  | [getIncludeStandardMetadataSignatures()](#getIncludeStandardMetadataSignatures--) | Author、Owner、ドキュメント作成日、更新日などの埋め込み標準ドキュメントメタデータ署名をメタデータリストに含めるフラグを取得または設定します。 |
|
|  | [setIncludeStandardMetadataSignatures(boolean value)](#setIncludeStandardMetadataSignatures-boolean-) | Author、Owner、ドキュメント作成日、更新日などの埋め込み標準ドキュメントメタデータ署名をメタデータリストに含めるフラグを取得または設定します。 |
|
|  | [getLogger()](#getLogger--) | ロギング（エラー、警告、トレース）に使用されるロガー実装です。 |
|
|  | [getLogLevel()](#getLogLevel--) | ロガーに渡されるメッセージの種類を取得または設定します。 |
|
|  | [setLogLevel(int value)](#setLogLevel-int-) | ロガーに渡されるメッセージの種類を取得または設定します。 |
|
### SignatureSettings() {#SignatureSettings--}
```
public SignatureSettings()
```


デフォルト値を持つデフォルトの SignatureSettings インスタンスを作成します。


### SignatureSettings(ILogger logger) {#SignatureSettings-com.groupdocs.signature.logging.ILogger-}
```
public SignatureSettings(ILogger logger)
```


Logger 実装を使用したデフォルトの SignatureSettings インスタンスを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| logger | [ILogger](../../com.groupdocs.signature.logging/ilogger) |  |

### getDefaultCulture() {#getDefaultCulture--}
```
public static Locale getDefaultCulture()
```


ドキュメント処理中に使用されるデフォルトのカルチャを取得または設定します。デフォルト値は "en-US" です。


**Returns:**
java.util.Locale
### setDefaultCulture(Locale value) {#setDefaultCulture-java.util.Locale-}
```
public final void setDefaultCulture(Locale value)
```


ドキュメント処理中に使用されるデフォルトのカルチャを取得または設定します。デフォルト値は "en-US" です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Locale |  |

### getShowDeletedSiganturesInfo() {#getShowDeletedSiganturesInfo--}
```
public final boolean getShowDeletedSiganturesInfo()
```


削除された署名を Document Info の結果に含めるフラグを取得または設定します。
各 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) には Deleted フラグがあります
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) は削除されたかどうかを検出するためのものです。


**Returns:**
boolean
### setShowDeletedSiganturesInfo(boolean value) {#setShowDeletedSiganturesInfo-boolean-}
```
public final void setShowDeletedSiganturesInfo(boolean value)
```


削除された署名を Document Info の結果に含めるフラグを取得または設定します。
各 Signature [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature) には Deleted フラグがあります
BaseSignature.Deleted
([BaseSignature.getDeleted](../../com.groupdocs.signature.domain.signatures/basesignature#getDeleted)/[BaseSignature.setDeleted(boolean)](../../com.groupdocs.signature.domain.signatures/basesignature#setDeleted-boolean-)) は削除されたかどうかを検出するためのものです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getSaveDocumentOnEmptyUpdate() {#getSaveDocumentOnEmptyUpdate--}
```
public final boolean getSaveDocumentOnEmptyUpdate()
```


Update メソッドに更新する署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。
このフラグが true（デフォルト）に設定されている場合、Update メソッドに更新する署名がなくても、ドキュメントは対応する履歴プロセスログ（日付と操作タイプ）とともに保存されます。
このフラグが false に設定されている場合、ソース ドキュメントはまったく変更されません。


**Returns:**
boolean
### setSaveDocumentOnEmptyUpdate(boolean value) {#setSaveDocumentOnEmptyUpdate-boolean-}
```
public final void setSaveDocumentOnEmptyUpdate(boolean value)
```


Update メソッドに更新する署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。
このフラグが true（デフォルト）に設定されている場合、Update メソッドに更新する署名がなくても、ドキュメントは対応する履歴プロセスログ（日付と操作タイプ）とともに保存されます。
このフラグが false に設定されている場合、ソース ドキュメントはまったく変更されません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getSaveDocumentOnEmptyDelete() {#getSaveDocumentOnEmptyDelete--}
```
public final boolean getSaveDocumentOnEmptyDelete()
```


Delete メソッドに削除対象の署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。
このフラグが true（デフォルト）に設定されている場合、ドキュメントは対応する履歴プロセスログ（日時と操作タイプ）とともに保存されます。たとえ Delete メソッドに削除すべき署名がなくてもです。
このフラグが false に設定されている場合、ソース ドキュメントはまったく変更されません。


**Returns:**
boolean
### setSaveDocumentOnEmptyDelete(boolean value) {#setSaveDocumentOnEmptyDelete-boolean-}
```
public final void setSaveDocumentOnEmptyDelete(boolean value)
```


Delete メソッドに削除対象の署名がない場合に、ソースドキュメントを再保存するフラグを取得または設定します。
このフラグが true（デフォルト）に設定されている場合、ドキュメントは対応する履歴プロセスログ（日時と操作タイプ）とともに保存されます。たとえ Delete メソッドに削除すべき署名がなくてもです。
このフラグが false に設定されている場合、ソース ドキュメントはまったく変更されません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getIncludeStandardMetadataSignatures() {#getIncludeStandardMetadataSignatures--}
```
public final boolean getIncludeStandardMetadataSignatures()
```


Author、Owner、ドキュメント作成日、更新日などの埋め込み標準ドキュメントメタデータ署名をメタデータリストに含めるフラグを取得または設定します。
このフラグが false（デフォルト）に設定されている場合、GetDocumentInfo はこれらのメタデータ署名を含みません。
このフラグが true に設定されている場合、ドキュメント情報はこれらの標準メタデータ署名を含みます。


**Returns:**
boolean
### setIncludeStandardMetadataSignatures(boolean value) {#setIncludeStandardMetadataSignatures-boolean-}
```
public final void setIncludeStandardMetadataSignatures(boolean value)
```


Author、Owner、ドキュメント作成日、更新日などの埋め込み標準ドキュメントメタデータ署名をメタデータリストに含めるフラグを取得または設定します。
このフラグが false（デフォルト）に設定されている場合、GetDocumentInfo はこれらのメタデータ署名を含みません。
このフラグが true に設定されている場合、ドキュメント情報はこれらの標準メタデータ署名を含みます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getLogger() {#getLogger--}
```
public final ILogger getLogger()
```


ロギング（エラー、警告、トレース）に使用されるロガー実装です。[ILogger](../../com.groupdocs.signature.logging/ilogger)。


**Returns:**
[ILogger](../../com.groupdocs.signature.logging/ilogger)
### getLogLevel() {#getLogLevel--}
```
public final int getLogLevel()
```


ロガーに渡されるメッセージの種類を取得または設定します。
この値は組み合わせ可能な [LogLevel](../../com.groupdocs.signature.logging/loglevel) フラグの集合です。例として

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
何も記録しません。
デフォルトは
LogLevel.All
：エラー、警告、トレースです。


**Returns:**
int
### setLogLevel(int value) {#setLogLevel-int-}
```
public final void setLogLevel(int value)
```


ロガーに渡されるメッセージの種類を取得または設定します。
この値は組み合わせ可能な [LogLevel](../../com.groupdocs.signature.logging/loglevel) フラグの集合です。例として

LogLevel.Error \| LogLevel.Warning
.
LogLevel.None
何も記録しません。
デフォルトは
LogLevel.All
：エラー、警告、トレースです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

