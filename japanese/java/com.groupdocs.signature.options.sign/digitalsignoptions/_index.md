---
title: "DigitalSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "デジタル署名オプションを表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

デジタル署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。 |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | DigitalSignOptions クラスの新しいインスタンスを証明書ファイルで初期化します。 |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | DigitalSignOptions クラスの新しいインスタンスを証明書ストリームで初期化します。 |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | DigitalSignOptions クラスの新しいインスタンスを証明書ファイルと画像ファイルで初期化します。 |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | DigitalSignOptions クラスの新しいインスタンスを証明書ファイルと画像ストリームで初期化します。 |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | DigitalSignOptions クラスの新しいインスタンスを証明書ストリームと画像ファイルで初期化します。 |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | DigitalSignOptions クラスの新しいインスタンスを証明書ストリームと画像ストリームで初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getReason()](#getReason--) | 署名の理由を取得または設定します。 |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 署名の理由を取得または設定します。 |
|
|  | [getContact()](#getContact--) | 署名の連絡先を取得または設定します。 |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 署名の連絡先を取得または設定します。 |
|
|  | [getLocation()](#getLocation--) | 署名の場所を取得または設定します。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 署名の場所を取得または設定します。 |
|
|  | [getPassword()](#getPassword--) | デジタル証明書のパスワードを取得または設定します。 |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | デジタル証明書のパスワードを取得または設定します。 |
|
|  | [getSignature()](#getSignature--) | 文書のデジタル署名のプロパティを取得または設定します。 |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | 文書のデジタル署名のプロパティを取得または設定します。 |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | デジタル証明書ファイルのパスを取得または設定します。 |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | デジタル証明書ファイルの GUID を取得または設定します。 |
|
|  | [getCertificateStream()](#getCertificateStream--) | デジタル証明書ストリームを取得または設定します。 |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | デジタル証明書ストリームを取得または設定します。 |
|
|  | [getVisible()](#getVisible--) | 署名の表示/非表示を取得または設定します。 |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 署名の表示/非表示を取得または設定します。 |
|
|  | [getUseLtv()](#getUseLtv--) | LTV（Long Term Validation）検証フラグを取得/設定します。 |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | LTV（Long Term Validation）検証フラグを取得/設定します。 |
|
|  | [getAllowExpired()](#getAllowExpired--) | 有効期限が切れた証明書での署名を許可するフラグを取得または設定します。 |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | 有効期限が切れた証明書での署名を許可するフラグを取得または設定します。 |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | 有効期間がまだ開始されていない証明書での署名を許可するフラグを取得または設定します。 |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | 有効期間がまだ開始されていない証明書での署名を許可するフラグを取得または設定します。 |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | カスタムハッシュ署名実装を取得または設定し、呼び出し元が独自の実装をプラグインできるようにします。 |
デジタル署名ロジック（HSM、リモート署名者、ソフトウェアキーストアなど）。
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | カスタムハッシュ署名実装を設定し、呼び出し元が独自の実装をプラグインできるようにします。 |
デジタル署名ロジック。
|
|  | [getXAdESType()](#getXAdESType--) | XAdES タイプ |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES タイプ |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


DigitalSignOptions クラスの新しいインスタンスをデフォルト値で初期化します。


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ファイルで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | デジタル証明書ファイルパス |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ストリームで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | デジタル証明書ストリーム |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ファイルと画像ファイルで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | デジタル証明書ファイルパス |
|
|  | imageFilePath | java.lang.String | 署名外観画像ファイルパス |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ファイルと画像ストリームで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | デジタル証明書ファイルパス |
|
|  | appearenceImageStream | java.io.InputStream | 署名外観画像ストリーム |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ストリームと画像ファイルで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | デジタル証明書ストリーム |
|
|  | imageFilePath | java.lang.String | 署名外観画像ファイルパス |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


DigitalSignOptions クラスの新しいインスタンスを証明書ストリームと画像ストリームで初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | デジタル証明書ストリーム |
|
|  | appearenceImageStream | java.io.InputStream | 署名外観画像ストリーム |
|

### getReason() {#getReason--}
```
public final String getReason()
```


署名の理由を取得または設定します。


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


署名の理由を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


署名の連絡先を取得または設定します。


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


署名の連絡先を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


署名の場所を取得または設定します。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


署名の場所を取得または設定します。


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

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


文書のデジタル署名のプロパティを取得または設定します。


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


文書のデジタル署名のプロパティを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


デジタル証明書ファイルのパスを取得または設定します。
このプロパティは CertificateStream が指定されていない場合にのみ使用されます。


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


デジタル証明書ファイルの GUID を取得または設定します。
このプロパティは CertificateStream が指定されていない場合にのみ使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


デジタル証明書ストリームを取得または設定します。
このプロパティが指定されている場合、常に CertificateGuid の代わりに使用されます。


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


デジタル証明書ストリームを取得または設定します。
このプロパティが指定されている場合、常に CertificateGuid の代わりに使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


署名の表示/非表示を取得または設定します。


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


署名の表示/非表示を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


LTV（Long Term Validation）検証フラグを取得/設定します。


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


LTV（Long Term Validation）検証フラグを取得/設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


有効期限が切れた証明書での署名を許可するフラグを取得または設定します。
デフォルト値は false です：期限切れの証明書で署名しようとすると例外がスローされます
GroupDocsSignatureException
,
そしてドキュメントは署名されません。


バリデータは期限切れの証明書で作成された署名を無効として報告します。このプロパティを true に設定するのは、
どうしてもそのような署名が必要な場合、例えば古い証明書でテストする場合です。その場合ドキュメントは署名され、そして
警告が設定されたロガーに書き込まれます
SignatureSettings
.


証明書は UTC の現在時刻と比較され、
DigitalSignature.SignTime
。このフラグ
は次の証明書に適用されます
CertificateFilePath
,
CertificateStream
または
署名
,
そして、スプレッドシートが署名されると、最初の証明書へ
DigitalVBA
拡張子。デジタル
画像の署名は証明書を使用せず、チェックされません。有効期間がまだ
開始されていないものは、次によって制御されます
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


有効期限が切れた証明書での署名を許可するフラグを取得または設定します。
デフォルト値は false です。#getAllowExpired().getAllowExpired() を参照してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


有効期間がまだ開始されていない証明書での署名を許可するフラグを取得または設定します。
デフォルト値は false です: そのような証明書で署名するとスローされます
GroupDocsSignatureException
,
そしてドキュメントは署名されません。


バリデータは、証明書が有効になる前に作成された署名を無効として報告します。そのような証明書は
通常は後日の発行であるか、コンピュータの時計が誤っています。このプロパティが true の場合、ドキュメントは
署名され、警告が設定されたロガーに書き込まれます
SignatureSettings
.


証明書は UTC の現在時刻と比較されます。このフラグは、次と同じ証明書に適用されます

AllowExpired
、有効期間が終了した証明書を制御します。


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


有効期間がまだ開始されていない証明書での署名を許可するフラグを取得または設定します。
デフォルト値は false です。#getAllowNotYetValid().getAllowNotYetValid() を参照してください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


カスタムハッシュ署名実装を取得または設定し、呼び出し元が独自の実装をプラグインできるようにします。
デジタル署名ロジック（HSM、リモート署名者、ソフトウェアキーストアなど）。


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


カスタムハッシュ署名実装を設定し、呼び出し元が独自の実装をプラグインできるようにします。
デジタル署名ロジック。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES タイプ
XAdESType
. デフォルト値は None です (XAdES はオフです)。
現在、XAdES 署名タイプは .NET Framework 上のスプレッドシート ドキュメントでのみサポートされており、.NET Standard ではサポートされていません。


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES タイプ
XAdESType
. デフォルト値は None です (XAdES はオフです)。
現在、XAdES 署名タイプは .NET Framework 上のスプレッドシート ドキュメントでのみサポートされており、.NET Standard ではサポートされていません。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
