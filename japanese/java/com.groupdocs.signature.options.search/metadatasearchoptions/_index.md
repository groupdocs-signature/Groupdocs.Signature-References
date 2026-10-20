---
title: "MetadataSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "メタデータ署名の抽象検索オプションを表します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

メタデータ署名の抽象検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | SearchMetadataOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 検索および一致させるべきメタデータ署名名を指定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 検索および一致させるべきメタデータ署名名を指定します。 |
|
|  | [getNameMatchType()](#getNameMatchType--) | メタデータ名の一致タイプ検索を取得または設定します。 |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | メタデータ名の一致タイプ検索を取得または設定します。 |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | ドキュメント統計や情報などの組み込みドキュメントプロパティを検索結果に含めるかどうかを示します。 |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | ドキュメント統計や情報などの組み込みドキュメントプロパティを検索結果に含めるかどうかを示します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


SearchMetadataOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### getName() {#getName--}
```
public final String getName()
```


検索および一致させるべきメタデータ署名名を指定します。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


検索および一致させるべきメタデータ署名名を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


メタデータ名の一致タイプ検索を取得または設定します。これは Name プロパティが設定されている場合にのみ使用されます。


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


メタデータ名の一致タイプ検索を取得または設定します。これは Name プロパティが設定されている場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


ドキュメント統計や情報などの組み込みドキュメントプロパティを検索結果に含めるかどうかを示します。
このフラグはプレゼンテーション、スプレッドシート、ワードプロセッシングのドキュメントファイルタイプに意味があります。


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


ドキュメント統計や情報などの組み込みドキュメントプロパティを検索結果に含めるかどうかを示します。
このフラグはプレゼンテーション、スプレッドシート、ワードプロセッシングのドキュメントファイルタイプに意味があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

