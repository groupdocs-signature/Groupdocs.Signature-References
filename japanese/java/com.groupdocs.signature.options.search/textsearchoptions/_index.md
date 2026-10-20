---
title: "TextSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "テキスト署名の検索オプションを表します。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

テキスト署名の検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | TextSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | TextSearchOptions クラスの新しいインスタンスをテキスト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getText()](#getText--) | 検索時に一致させる署名テキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 検索時に一致させる署名テキストを指定します。 |
|
|  | [getMatchType()](#getMatchType--) | テキストの一致タイプ検索を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | テキストの一致タイプ検索を取得または設定します。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 検索対象のテキスト署名実装を指定します。 |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | 検索対象のテキスト署名実装を指定します。 |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


TextSearchOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
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


検索時に一致させる署名テキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


検索時に一致させる署名テキストを指定します。


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


検索対象のテキスト署名実装を指定します。


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


検索対象のテキスト署名実装を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

