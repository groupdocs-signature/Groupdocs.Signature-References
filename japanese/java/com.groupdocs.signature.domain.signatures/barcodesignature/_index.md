---
title: "BarcodeSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "バーコード署名のプロパティを含みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.signatures/barcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class BarcodeSignature extends BaseSignature
```

バーコード署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [BarcodeSignature(String signatureId)](#BarcodeSignature-java.lang.String-) | 検索プロセス後に取得した署名識別子で BarcodeSignature オブジェクトを初期化する。 |
|
|  | [BarcodeSignature()](#BarcodeSignature--) | デフォルトパラメータで BarcodeSignature を初期化する。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | バーコードエンコードタイプを指定します。 |
|
|  | [getText()](#getText--) | バーコードのテキストを指定します。 |
|
|  | [getFormat()](#getFormat--) | バーコード署名画像の形式を指定します。 |
|
|  | [getContent()](#getContent--) | タイプのバーコードバイナリデータ画像コンテンツを指定します |
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Barcode Signature インスタンスをクローンします。 |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### BarcodeSignature(String signatureId) {#BarcodeSignature-java.lang.String-}
```
public BarcodeSignature(String signatureId)
```


検索プロセス後に取得した署名識別子で BarcodeSignature オブジェクトを初期化する。
このユニークな識別子は、ドキュメント署名情報層からこのシグネチャの追加プロパティを検索するために使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureId | java.lang.String | Signature クラスの Sign または Search メソッドで取得されたユニークな署名識別子 [Signature](../../com.groupdocs.signature/signature)。 |
|

### BarcodeSignature() {#BarcodeSignature--}
```
public BarcodeSignature()
```


デフォルトパラメータで BarcodeSignature を初期化する。


### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


バーコードエンコードタイプを指定します。


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### getText() {#getText--}
```
public final String getText()
```


バーコードのテキストを指定します。


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


バーコード署名画像の形式を指定します。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


タイプのバーコードバイナリデータ画像コンテンツを指定します
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
デフォルトではこのプロパティは設定されません。
プロパティを使用してください
BarcodeSearchOptions.ReturnContent
([BarcodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/barcodesearchoptions#getReturnContent)/[BarcodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/barcodesearchoptions#setReturnContent-boolean-)) この機能を有効にするには。


**Returns:**
byte[]
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

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 画像 | java.awt.image.BufferedImage |  |

