---
title: "DigitalSignatureAppearance"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "デジタル署名の署名ラインの外観を説明します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

デジタル署名の署名ラインの外観を説明します。
1 つの署名行は 1 つのデジタル署名にのみ適用できます。
署名行は常に最初のページにあります。
この機能は .docx、.doc、.odt、.xlsx ファイル形式で役立つ可能性があります。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | 署名行の外観オブジェクトを作成します。 |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | 指定された値（署名者、タイトル、メール）で署名行の外観を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSigner()](#getSigner--) | 署名行の署名者名を取得または設定します。 |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | 署名行の署名者名を取得または設定します。 |
|
|  | [getTitle()](#getTitle--) | 署名行のタイトルを取得または設定します。 |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 署名行のタイトルを取得または設定します。 |
|
|  | [getEmail()](#getEmail--) | 署名行に表示されるメールアドレスを取得または設定します。 |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | 署名行に表示されるメールアドレスを取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


署名行の外観オブジェクトを作成します。


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


指定された値（署名者、タイトル、メール）で署名行の外観を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 署名者 | java.lang.String | 署名者名。 |
|
|  | タイトル | java.lang.String | 署名タイトル。 |
|
|  | メール | java.lang.String | 作者のメール。 |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


署名行の署名者名を取得または設定します。


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


署名行の署名者名を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


署名行のタイトルを取得または設定します。


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


署名行のタイトルを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


署名行に表示されるメールアドレスを取得または設定します。


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


署名行に表示されるメールアドレスを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
