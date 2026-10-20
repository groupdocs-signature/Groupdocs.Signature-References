---
title: "SearchOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントから署名を抽出するオプションを表します。"
type: docs
weight: 17
url: /ja/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

ドキュメントから署名を抽出するオプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 検索対象のドキュメントページ番号を取得または設定します。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 検索対象のドキュメントページ番号を取得または設定します。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 署名検索のページを指定するオプション。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 署名検索のページを指定するオプション。 |
|
|  | [getAllPages()](#getAllPages--) | 各ドキュメントページで検索するフラグ。 |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 各ドキュメントページで検索するフラグ。 |
|
|  | [getSkipExternal()](#getSkipExternal--) | IsSignature とマークされた署名のみを返すフラグです。 |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | IsSignature とマークされた署名のみを返すフラグです。 |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | 署名抽出のためのページリストを取得する仮想メソッドです。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


検索対象のドキュメントページ番号を取得または設定します。
この値はオプションです。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


検索対象のドキュメントページ番号を取得または設定します。
この値はオプションです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


署名検索のページを指定するオプション。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


署名検索のページを指定するオプション。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


各ドキュメントページで検索するフラグです。デフォルトではこの値は true に設定されています。


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


各ドキュメントページで検索するフラグです。デフォルトではこの値は true に設定されています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


IsSignature とマークされた署名のみを返すフラグです。デフォルト値は false で、指定された条件に一致するすべての署名を返すことを示します。


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


IsSignature とマークされた署名のみを返すフラグです。デフォルト値は false で、指定された条件に一致するすべての署名を返すことを示します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


署名抽出のためのページリストを取得する仮想メソッドです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | totalPages | int | ページの総数 |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - ページ番号のリスト

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
