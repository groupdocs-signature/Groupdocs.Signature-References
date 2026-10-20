---
title: "DigitalVBA"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "スプレッドシートの VBA プロジェクト用デジタル署名を表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

スプレッドシートの VBA プロジェクト用デジタル署名を表します。
Xlsm や Xltm のような特定のスプレッドシート文書形式で VBA プロジェクトに署名する機能を提供します。
複数の DigitalVBA 拡張機能が DigitalSignOptions.Extensions に追加された場合、最初のものだけが文書署名に使用されます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | 証明書ファイルで DigitalVBA クラスの新しいインスタンスを初期化します。 |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | 証明書ストリームで DigitalVBA クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getComments()](#getComments--) | 署名コメントを取得または設定します。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 署名コメントを取得または設定します。 |
|
|  | [getPassword()](#getPassword--) | デジタル証明書のパスワードを取得または設定します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | デジタル証明書のパスワードを取得または設定します。 |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | VBA プロジェクトの署名のみの設定を取得または設定します。 |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | VBA プロジェクトの署名のみの設定を取得または設定します。 |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | デジタル証明書ファイルのパスを取得します。 |
|
|  | [getCertificateStream()](#getCertificateStream--) | デジタル証明書ストリームを取得します。 |
|
|  | [release()](#release--) | 署名後にリソースをクリーンアップするためにメソッドをオーバーライドします。 |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


証明書ファイルで DigitalVBA クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | デジタル証明書ファイルパス |
|
|  | パスワード | java.lang.String | デジタル証明書のパスワード |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


証明書ストリームで DigitalVBA クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | デジタル証明書ストリーム |
|
|  | パスワード | java.lang.String | デジタル証明書のパスワード |
|

### getComments() {#getComments--}
```
public final String getComments()
```


署名コメントを取得または設定します。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


署名コメントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


デジタル証明書のパスワードを取得または設定します。


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


デジタル証明書のパスワードを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


VBA プロジェクトの署名のみの設定を取得または設定します。
true に設定すると、SpreadSheet 文書は署名されず、VBA プロジェクトのみが署名されます。


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


VBA プロジェクトの署名のみの設定を取得または設定します。
true に設定すると、SpreadSheet 文書は署名されず、VBA プロジェクトのみが署名されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


デジタル証明書ファイルのパスを取得します。
このプロパティは CertificateStream が指定されていない場合にのみ使用されます。


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


デジタル証明書ストリームを取得します。
このプロパティが指定されている場合、常に CertificateFilePath の代わりに使用されます。


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


署名後にリソースをクリーンアップするためにメソッドをオーバーライドします。


