---
title: "QrCodeVerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "ドキュメントの QR コード署名を検証するオプションを保持します。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

ドキュメントの QR コード署名を検証するオプションを保持します。

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。 |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | 検証するQRコードテキストを含む、QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。 |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | テキストと検証するQRコードエンコードタイプを含む、QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QRコードタイプの検証を取得または設定します。 |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRコードタイプの検証を取得または設定します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | QRコード署名テキストプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QRコード署名テキストプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドする。 |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


検証するQRコードテキストを含む、QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証するQRコードテキスト |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


テキストと検証するQRコードエンコードタイプを含む、QRコード署名用の検証オプション QRCodeVerifyOptions を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証対象テキスト |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | エンコードの種類 |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRコードタイプの検証を取得または設定します。このプロパティはオプションです。


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRコードタイプの検証を取得または設定します。このプロパティはオプションです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QRコード署名テキストプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QRコード署名テキストプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドする。


**Returns:**
java.lang.String -
