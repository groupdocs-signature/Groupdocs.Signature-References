---
title: "QrCodeSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "QRコード署名のプロパティを含みます。"
type: docs
weight: 16
url: /ja/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

QRコード署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | 検索プロセス後に取得された署名識別子で QrCodeSignature オブジェクトを初期化します。 |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR コードのエンコードタイプを指定します。 |
|
|  | [getText()](#getText--) | QR コードのテキストを指定します。 |
|
|  | [getFormat()](#getFormat--) | QR コード署名画像のフォーマットを指定します。 |
|
|  | [getContent()](#getContent--) | タイプの QR コード バイナリデータ画像コンテンツを指定します。 |
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | デシリアライズ時に QR-Code 署名テキストからオブジェクトを取得します。 |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | デシリアライズ時に QR-Code 署名テキストからオブジェクトを取得します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | QR-Code 署名インスタンスをクローンします。 |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


検索プロセス後に取得された署名識別子で QrCodeSignature オブジェクトを初期化します。
このユニークな識別子は、ドキュメント署名情報層からこのシグネチャの追加プロパティを検索するために使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureId | java.lang.String | サインまたは検索メソッドで取得されたユニークなシグネチャ識別子。 |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR コードのエンコードタイプを指定します。


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


QR コードのテキストを指定します。


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


QR コード署名画像のフォーマットを指定します。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


タイプの QR コード バイナリデータ画像コンテンツを指定します。
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
デフォルトではこのプロパティは設定されません。
プロパティを使用してください
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) この機能を有効にするには。


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


デシリアライズ時に QR-Code 署名テキストからオブジェクトを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| タイプ | java.lang.Class<T> |  |

**Returns:**
T -
T
: QRコードテキストからデシリアライズするオブジェクトの型

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


デシリアライズ時に QR-Code 署名テキストからオブジェクトを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | カスタムデータ暗号化実装を設定する |


T
: QRコードテキストからデシリアライズするオブジェクトの型
|
| タイプ | java.lang.Class<T> |  |

**Returns:**
T -
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


QR-Code 署名インスタンスをクローンします。


**Returns:**
java.lang.Object - クローンされた QRコード 署名インスタンスを返します。

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 画像 | java.awt.image.BufferedImage |  |

