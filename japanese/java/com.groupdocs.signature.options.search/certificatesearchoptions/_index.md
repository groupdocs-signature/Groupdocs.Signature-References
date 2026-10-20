---
title: "CertificateSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "証明書メタデータ署名の検索オプションを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

証明書メタデータ署名の検索オプションを表します。

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | TextSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | TextSearchOptions クラスの新しいインスタンスをテキスト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getText()](#getText--) | 検索時に一致させる証明書プロパティテキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 検索時に一致させる証明書プロパティテキストを指定します。 |
|
|  | [getMatchType()](#getMatchType--) | テキストの一致タイプ検索を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | テキストの一致タイプ検索を取得または設定します。 |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


TextSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


TextSearchOptions クラスの新しいインスタンスをテキスト値で初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | テキスト署名のテキストを設定します。 |
|

### getText() {#getText--}
```
public final String getText()
```


検索時に一致させる証明書プロパティテキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


検索時に一致させる証明書プロパティテキストを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


テキストの一致タイプ検索を取得または設定します。


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


テキストの一致タイプ検索を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

