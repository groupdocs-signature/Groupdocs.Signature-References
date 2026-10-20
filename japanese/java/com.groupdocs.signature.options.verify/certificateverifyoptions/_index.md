---
title: "CertificateVerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "証明書ドキュメントを検証するオプションを保持します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object、 [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

証明書ドキュメントを検証するオプションを保持します。

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | デフォルト値で TextVerifyOptions の新しいインスタンスを初期化します。 |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | 検証対象のサブジェクトを持つ CertificateVerifyOptions の新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | 検証する場合は、証明書の発行者を指定してください。 |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | 検証する場合は、証明書の発行者を指定してください。 |
|
|  | [getSerialNumber()](#getSerialNumber--) | 検証する場合は、証明書のシリアル番号を指定してください。 |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 検証する場合は、証明書のシリアル番号を指定してください。 |
|
|  | [getSubject()](#getSubject--) | 検証する場合は、証明書のサブジェクトを指定してください。 |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 検証する場合は、証明書のサブジェクトを指定してください。 |
|
|  | [getThumbprint()](#getThumbprint--) | 検証する場合は、証明書のサムプリントを指定してください。 |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | 検証する場合は、証明書のサムプリントを指定してください。 |
|
|  | [getMatchType()](#getMatchType--) | テキストマッチタイプの検証を取得または設定します。 |
|
|  | [setMatchType(int value)](#setMatchType-int-) | テキストマッチタイプの検証を取得または設定します。 |
|
|  | [getExpired()](#getExpired--) | 検証結果に基づき、証明書が有効期限切れかどうかを示します。 |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | 検証結果に基づき、証明書が有効期限切れかどうかを示します。 |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | 基本検証ポリシーを使用した X.509 チェーン検証を提供すべきかどうかを取得または設定します。 |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | 基本検証ポリシーを使用した X.509 チェーン検証を提供すべきかどうかを取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドする。 |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


デフォルト値で TextVerifyOptions の新しいインスタンスを初期化します。


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


検証対象のサブジェクトを持つ CertificateVerifyOptions の新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 件名 | java.lang.String | 検証対象サブジェクト |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


検証する場合は、証明書の発行者を指定してください。


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


検証する場合は、証明書の発行者を指定してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


検証する場合は、証明書のシリアル番号を指定してください。


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


検証する場合は、証明書のシリアル番号を指定してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


検証する場合は、証明書のサブジェクトを指定してください。


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


検証する場合は、証明書のサブジェクトを指定してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


検証する場合は、証明書のサムプリントを指定してください。


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


検証する場合は、証明書のサムプリントを指定してください。


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

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


検証結果に基づき、証明書が有効期限切れかどうかを示します。
プロパティは読み取り専用です。


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


検証結果に基づき、証明書が有効期限切れかどうかを示します。
プロパティは読み取り専用です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


基本検証ポリシーを使用した X.509 チェーン検証を提供すべきかどうかを取得または設定します。
デフォルトではこの値は true です。


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


基本検証ポリシーを使用した X.509 チェーン検証を提供すべきかどうかを取得または設定します。
デフォルトではこの値は true です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドする。


**Returns:**
java.lang.String -
