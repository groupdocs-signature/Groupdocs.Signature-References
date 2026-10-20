---
title: "SignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "署名オプションを表します。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.options.sign/signoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class SignOptions
```

署名オプションを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 署名対象のドキュメントページ番号を取得または設定します。 |
|
|  | [setPageNumber(int value)](#setPageNumber-int-) | 署名対象のドキュメントページ番号を取得または設定します。 |
|
|  | [getAllPages()](#getAllPages--) | すべてのドキュメントページに署名を配置します。 |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | すべてのドキュメントページに署名を配置します。 |
|
|  | [getAppearance()](#getAppearance--) | 追加の署名外観。 |
|
|  | [setAppearance(SignatureAppearance value)](#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-) | 追加の署名外観。 |
|
|  | [getExtensions()](#getExtensions--) | 署名拡張機能。 |
|
|  | [setExtensions(List<SignatureExtension> value)](#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--) | 署名拡張機能。 |
|
|  | [getPagesSetup()](#getPagesSetup--) | 署名対象ページを指定するオプションです。 |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 署名対象ページを指定するオプションです。 |
|
|  | [getSignatureType()](#getSignatureType--) | 署名タイプを取得します [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype) |
|
|  | [getDocumentType()](#getDocumentType--) | 署名オプションのドキュメントタイプを取得または設定します [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [setDocumentType(int value)](#setDocumentType-int-) | 署名オプションのドキュメントタイプを取得または設定します [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype) |
|
|  | [getZOrder()](#getZOrder--) | テキスト署名の Z オーダー位置を取得または設定します。 |
|
|  | [setZOrder(int value)](#setZOrder-int-) | テキスト署名の Z オーダー位置を取得または設定します。 |
|
|  | [getHashAlgorithm()](#getHashAlgorithm--) | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。 |
|
|  | [setHashAlgorithm(int value)](#setHashAlgorithm-int-) | 暗号操作に使用されるハッシュアルゴリズムを取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
| [addSignature(Object[] args)](#addSignature-java.lang.Object...-) |  |
### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


署名対象のドキュメントページ番号を取得または設定します。
最小値およびデフォルト値は 1 です。


**Returns:**
int
### setPageNumber(int value) {#setPageNumber-int-}
```
public void setPageNumber(int value)
```


署名対象のドキュメントページ番号を取得または設定します。
最小値およびデフォルト値は 1 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getAllPages() {#getAllPages--}
```
public boolean getAllPages()
```


すべてのドキュメントページに署名を配置します。


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public void setAllPages(boolean value)
```


すべてのドキュメントページに署名を配置します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getAppearance() {#getAppearance--}
```
public final SignatureAppearance getAppearance()
```


追加の署名外観。


**Returns:**
[SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
### setAppearance(SignatureAppearance value) {#setAppearance-com.groupdocs.signature.options.appearances.SignatureAppearance-}
```
public final void setAppearance(SignatureAppearance value)
```


追加の署名外観。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance) |  |

### getExtensions() {#getExtensions--}
```
public final List<SignatureExtension> getExtensions()
```


署名拡張機能。


**Returns:**
java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension>
### setExtensions(List<SignatureExtension> value) {#setExtensions-java.util.List-com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension--}
```
public void setExtensions(List<SignatureExtension> value)
```


署名拡張機能。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.List<com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension> |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


署名対象ページを指定するオプションです。


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


署名対象ページを指定するオプションです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


署名タイプを取得します [SignatureType](../../com.groupdocs.signature.domain.enums/signaturetype)


**Returns:**
int
### getDocumentType() {#getDocumentType--}
```
public final int getDocumentType()
```


署名オプションのドキュメントタイプを取得または設定します [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Returns:**
int
### setDocumentType(int value) {#setDocumentType-int-}
```
public final void setDocumentType(int value)
```


署名オプションのドキュメントタイプを取得または設定します [DocumentType](../../com.groupdocs.signature.domain.enums/documenttype)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getZOrder() {#getZOrder--}
```
public final int getZOrder()
```


テキスト署名の Z オーダー位置を取得または設定します。
重なり合う署名の表示順序を決定します。


**Returns:**
int
### setZOrder(int value) {#setZOrder-int-}
```
public final void setZOrder(int value)
```


テキスト署名の Z オーダー位置を取得または設定します。
重なり合う署名の表示順序を決定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getHashAlgorithm() {#getHashAlgorithm--}
```
public final int getHashAlgorithm()
```


暗号操作に使用されるハッシュアルゴリズムを取得または設定します。
PDF ファイルのデジタル署名にのみ対応しています。
値は [HashAlgorithm](../../com.groupdocs.signature.domain.enums/hashalgorithm) の定数のいずれかです。


**Returns:**
int
### setHashAlgorithm(int value) {#setHashAlgorithm-int-}
```
public final void setHashAlgorithm(int value)
```


暗号操作に使用されるハッシュアルゴリズムを取得または設定します。
PDF ファイルのデジタル署名にのみ対応しています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
### addSignature(Object[] args) {#addSignature-java.lang.Object...-}
```
public BaseSignature addSignature(Object[] args)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| args | java.lang.Object[] |  |

**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
