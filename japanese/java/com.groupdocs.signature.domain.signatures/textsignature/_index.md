---
title: "TextSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "テキスト署名のプロパティを含みます。"
type: docs
weight: 18
url: /ja/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

テキスト署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | 検索プロセス後に取得されたシグネチャ識別子で TextSignature オブジェクトを初期化します。 |
|
| [TextSignature()](#TextSignature--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getText()](#getText--) | シグネチャ内のテキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | シグネチャ内のテキストを指定します。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | テキストシグネチャの実装を指定します。 |
|
|  | [getNative()](#getNative--) | ネイティブ属性を指定します。 |
|
|  | [setNative(boolean value)](#setNative-boolean-) | ネイティブ属性を指定します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Text Signature インスタンスをクローンします。 |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


検索プロセス後に取得されたシグネチャ識別子で TextSignature オブジェクトを初期化します。
このユニークな識別子は、ドキュメント署名情報層からこのシグネチャの追加プロパティを検索するために使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureId | java.lang.String | サインまたは検索メソッドで取得されたユニークなシグネチャ識別子。 |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


シグネチャ内のテキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


シグネチャ内のテキストを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


テキストシグネチャの実装を指定します。


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


ネイティブ属性を指定します。シグネチャがドキュメント固有の場合は true です。


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


ネイティブ属性を指定します。シグネチャがドキュメント固有の場合は true です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


署名プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signature | java.lang.Object | 比較対象となる Signature オブジェクト。 |
|

**Returns:**
boolean - 渡された signature オブジェクトが同じ型であり、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Signature のハッシュコード

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Text Signature インスタンスをクローンします。


**Returns:**
java.lang.Object - クローンされたテキスト署名インスタンスを返します。

