---
title: "TextVerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントのテキスト署名を検証するオプションを保持します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

ドキュメントのテキスト署名を検証するオプションを保持します。

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | デフォルト値で TextVerifyOptions の新しいインスタンスを初期化します。 |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | 検証テキストで TextVerifyOptions の新しいインスタンスを初期化します。 |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | 検証する Text プロパティと署名実装を指定して TextVerifyOptions の新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getText()](#getText--) | 検証すべき署名テキストを指定します。 |
|
|  | [setText(String value)](#setText-java.lang.String-) | 検証すべき署名テキストを指定します。 |
|
|  | [getMatchType()](#getMatchType--) | テキストマッチタイプの検証を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | テキストマッチタイプの検証を取得または設定します。 |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 検証対象の署名のタイプ。 |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | 検証対象の署名のタイプ。 |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | 検証対象のフォームフィールドのタイトルを取得または設定します。 |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | 検証対象のフォームフィールドのタイトルを取得または設定します。 |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | 検証対象のフォームフィールドのタイプを取得または設定します。 |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | 検証対象のフォームフィールドのタイプを取得または設定します。 |
|
|  | [getSignatureID()](#getSignatureID--) | 検証する場合は、テキスト署名IDを0より大きく指定してください。 |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 検証する場合は、テキスト署名IDを0より大きく指定してください。 |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドする。 |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


デフォルト値で TextVerifyOptions の新しいインスタンスを初期化します。


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


検証テキストで TextVerifyOptions の新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証対象テキスト |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


検証する Text プロパティと署名実装を指定して TextVerifyOptions の新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証対象テキスト。 |
|
|  | 実装 | int | 署名実装タイプ。 |
|

### getText() {#getText--}
```
public final String getText()
```


検証すべき署名テキストを指定します。


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


検証すべき署名テキストを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


テキストマッチタイプの検証を取得または設定します。


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


テキストマッチタイプの検証を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


検証対象の署名のタイプ。


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


検証対象の署名のタイプ。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


検証対象のフォームフィールドのタイトルを取得または設定します。
このプロパティが設定されている場合、テキストはテキストフォームフィールド内でのみ見つかります。


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


検証対象のフォームフィールドのタイトルを取得または設定します。
このプロパティが設定されている場合、テキストはテキストフォームフィールド内でのみ見つかります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


検証対象のフォームフィールドのタイプを取得または設定します。
このプロパティが設定されている場合、テキストはテキストフォームフィールド内でのみ見つかります。


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


検証対象のフォームフィールドのタイプを取得または設定します。
このプロパティが設定されている場合、テキストはテキストフォームフィールド内でのみ見つかります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


検証する場合は、テキスト署名IDを0より大きく指定してください。このプロパティはPDFドキュメントでのみサポートされます。


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


検証する場合は、テキスト署名IDを0より大きく指定してください。このプロパティはPDFドキュメントでのみサポートされます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドする。


**Returns:**
java.lang.String -
