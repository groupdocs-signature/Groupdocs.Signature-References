---
title: "VerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントを検証するオプションを保持します。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

ドキュメントを検証するオプションを保持します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [isValid()](#isValid--) | 有効なプロパティフラグ。 |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 有効なプロパティフラグ。 |
|
|  | [getPageNumber()](#getPageNumber--) | 検証対象のドキュメントページ番号。 |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 検証対象のドキュメントページ番号。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 検証するページを指定するページオプション。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 検証するページを指定するページオプション。 |
|
|  | [getAllPages()](#getAllPages--) | 各ドキュメントページを検証するフラグ。 |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 各ドキュメントページを検証するフラグ。 |
|
|  | [getExtensions()](#getExtensions--) | 代替署名オプションの検証用追加拡張。 |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | 代替署名オプションの検証用追加拡張。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


有効なプロパティフラグ。


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


有効なプロパティフラグ。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


検証対象のドキュメントページ番号。プロパティが設定されていない場合、すべてのページが対象です
ドキュメントは最初の出現箇所で検証されます。
最小値は 1 です。


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


検証対象のドキュメントページ番号。プロパティが設定されていない場合、すべてのページが対象です
ドキュメントは最初の出現箇所で検証されます。
最小値は 1 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


検証するページを指定するページオプション。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


検証するページを指定するページオプション。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


各ドキュメントページを検証するフラグ。デフォルト値は true です。


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


各ドキュメントページを検証するフラグ。デフォルト値は true です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


代替署名オプションの検証用追加拡張。


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


代替署名オプションの検証用追加拡張。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
