---
title: "DigitalSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "デジタル署名のプロパティを含みます。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

デジタル署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | デフォルトパラメーターで Digital signature を初期化します。 |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | 既知の SignatureId で Digital signature を初期化します。 |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | 指定された証明書で Digital signature を作成します。 |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | X509Certificate 証明書と PrivateKey に基づいて Digital signature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | KeyStore 証明書を取得または設定します。 |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | KeyStore 証明書を取得または設定します。 |
|
|  | [getX509Certificate()](#getX509Certificate--) | X509 証明書を取得または設定します。 |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | X509 証明書を取得または設定します。 |
|
|  | [getPrivateKey()](#getPrivateKey--) | 証明書の PrivateKey を取得または設定します。 |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | 証明書の PrivateKey を取得または設定します。 |
|
|  | [getCertificateName()](#getCertificateName--) | X509 証明書名を取得または設定します。 |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | X509 証明書名を取得または設定します。 |
|
|  | [getComments()](#getComments--) | 署名目的コメントを取得または設定します。 |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 署名目的コメントを取得または設定します。 |
|
|  | [isValid()](#isValid--) | このデジタル署名が有効で、文書が改ざんされていない場合は true を保持します。 |
|
|  | [setValid(boolean value)](#setValid-boolean-) | このデジタル署名が有効で、文書が改ざんされていない場合は true を保持します。 |
|
|  | [getSignTime()](#getSignTime--) | 文書が署名された時刻を取得または設定します。 |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | 文書が署名された時刻を取得または設定します。 |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES タイプ |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES タイプ |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | 証明書のサムプリントを取得します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Barcode Signature インスタンスをクローンします。 |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | システム内のすべての X509 証明書ストアからデジタル署名をロードします。 |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | 渡された X509 証明書ストアからデジタル署名をロードします。 |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


デフォルトパラメーターで Digital signature を初期化します。


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


既知の SignatureId で Digital signature を初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


指定された証明書で Digital signature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 証明書 | java.security.KeyStore | X509 証明書です。 |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


X509Certificate 証明書と PrivateKey に基づいて Digital signature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate 証明書。 |
|
|  | key | java.security.PrivateKey | 証明書の PrivateKey。 |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


KeyStore 証明書を取得または設定します。


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


KeyStore 証明書を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


X509 証明書を取得または設定します。


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


X509 証明書を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


証明書の PrivateKey を取得または設定します。


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


証明書の PrivateKey を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


X509 証明書名を取得または設定します。


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


X509 証明書名を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


署名目的コメントを取得または設定します。


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


署名目的コメントを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


このデジタル署名が有効で、文書が改ざんされていない場合は true を保持します。


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


このデジタル署名が有効で、文書が改ざんされていない場合は true を保持します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


文書が署名された時刻を取得または設定します。


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


文書が署名された時刻を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES タイプ
XAdESType
. デフォルト値は None です (XAdES はオフです)。
現在、XAdES 署名タイプはスプレッドシート文書でのみサポートされています。


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES タイプ
XAdESType
. デフォルト値は None です (XAdES はオフです)。
現在、XAdES 署名タイプはスプレッドシート文書でのみサポートされています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


証明書のサムプリントを取得します。


**Returns:**
java.lang.String
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


Barcode Signature インスタンスをクローンします。


**Returns:**
java.lang.Object - クローンされた Barcode Signature インスタンスを返します。

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


システム内のすべての X509 証明書ストアからデジタル署名をロードします。


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) デジタル署名のリストを返します。

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


渡された X509 証明書ストアからデジタル署名をロードします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) デジタル署名のリストを返します。

