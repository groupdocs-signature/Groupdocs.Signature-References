---
title: "BarcodeVerifyOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "バーコード検証オプションを表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.options.verify/barcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class BarcodeVerifyOptions extends TextVerifyOptions
```

バーコード検証オプションを表します。

<br />

*** ** * ** ***

 **Learn more**  **Learn more**

* Basic usage of verification for Barcode electronic signature by GroupDocs.Signature: [How to eVerification Barcode signatures in a document](../https://docs.groupdocs.com/signature/java/verify-barcode-signatures-in-the-document)
* Advanced usage of settings of verification for Barcode electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Barcode signatures in a document and additional settings](../)

<br />


## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BarcodeVerifyOptions()](#BarcodeVerifyOptions--) | バーコード署名のデフォルト検証オプションを作成します。 |
|
|  | [BarcodeVerifyOptions(String text)](#BarcodeVerifyOptions-java.lang.String-) | 検証テキストを使用したデフォルト検証オプションを作成します |
|
|  | [BarcodeVerifyOptions(BarcodeType encodeType)](#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | バーコードタイプの検証を使用したデフォルト検証オプションを作成します |
|
|  | [BarcodeVerifyOptions(String text, BarcodeType encodeType)](#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | バーコードタイプの検証とテキストを使用したデフォルト検証オプションを作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | バーコードタイプの検証を取得または設定します。 |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | バーコードタイプの検証を取得または設定します。 |
|
|  | [toString()](#toString--) | 文字列への変換をオーバーライドする。 |
|
### BarcodeVerifyOptions() {#BarcodeVerifyOptions--}
```
public BarcodeVerifyOptions()
```


バーコード署名のデフォルト検証オプションを作成します。


### BarcodeVerifyOptions(String text) {#BarcodeVerifyOptions-java.lang.String-}
```
public BarcodeVerifyOptions(String text)
```


検証テキストを使用したデフォルト検証オプションを作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証するバーコードテキスト |
|

### BarcodeVerifyOptions(BarcodeType encodeType) {#BarcodeVerifyOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(BarcodeType encodeType)
```


バーコードタイプの検証を使用したデフォルト検証オプションを作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | バーコードタイプの検証 |
|

### BarcodeVerifyOptions(String text, BarcodeType encodeType) {#BarcodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeVerifyOptions(String text, BarcodeType encodeType)
```


バーコードタイプの検証とテキストを使用したデフォルト検証オプションを作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | テキスト | java.lang.String | 検証するバーコードテキスト |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | バーコードタイプの検証 |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


バーコードタイプの検証を取得または設定します。


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


バーコードタイプの検証を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### toString() {#toString--}
```
public String toString()
```


文字列への変換をオーバーライドする。


**Returns:**
java.lang.String -
