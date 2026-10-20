---
title: "FormFieldSearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "フォームフィールド署名の抽象検索オプションを表します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

フォームフィールド署名の抽象検索オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | SearchFormFieldOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getType()](#getType--) | 検索対象の場合、フォームフィールド署名のタイプを指定します。 |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | 検索対象の場合、フォームフィールド署名のタイプを指定します。 |
|
|  | [getName()](#getName--) | 検索対象の場合、フォームフィールド署名名の正規表現パターンを指定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 検索対象の場合、フォームフィールド署名名の正規表現パターンを指定します。 |
|
|  | [getValue()](#getValue--) | 検索対象の場合、フォームフィールド署名の値を指定します。 |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 検索対象の場合、フォームフィールド署名の値を指定します。 |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


SearchFormFieldOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### getType() {#getType--}
```
public final Integer getType()
```


検索対象の場合、フォームフィールド署名のタイプを指定します。デフォルト値は null です。


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


検索対象の場合、フォームフィールド署名のタイプを指定します。デフォルト値は null です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


検索対象の場合、フォームフィールド署名名の正規表現パターンを指定します。
シンプルに "text" として、または "abc\\d+" のような正規表現として使用できます。デフォルト値は空文字列です。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


検索対象の場合、フォームフィールド署名名の正規表現パターンを指定します。
シンプルに "text" として、または "abc\\d+" のような正規表現として使用できます。デフォルト値は空文字列です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


検索対象の場合、フォームフィールド署名の値を指定します。デフォルト値は null です。


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


検索対象の場合、フォームフィールド署名の値を指定します。デフォルト値は null です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

