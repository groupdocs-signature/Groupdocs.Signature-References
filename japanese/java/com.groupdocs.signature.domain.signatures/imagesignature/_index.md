---
title: "ImageSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像署名のプロパティを含みます。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.domain.signatures/imagesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class ImageSignature extends BaseSignature
```

画像署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ImageSignature(String signatureId)](#ImageSignature-java.lang.String-) | 検索プロセス後に取得した署名識別子で ImageSignature オブジェクトを初期化します。 |
|
|  | [ImageSignature()](#ImageSignature--) | デフォルトパラメーターで ImageSignature を初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSize()](#getSize--) | 署名画像のサイズ（バイト単位）を指定します。 |
|
|  | [setSize(int value)](#setSize-int-) | 署名画像のサイズ（バイト単位）を指定します。 |
|
|  | [getFormat()](#getFormat--) | 署名画像の形式を指定します。 |
|
|  | [setFormat(FileType value)](#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-) | 署名画像の形式を指定します。 |
|
|  | [getContent()](#getContent--) | タイプの画像バイナリデータ内容を指定します。 |
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Barcode Signature インスタンスをクローンします。 |
|
### ImageSignature(String signatureId) {#ImageSignature-java.lang.String-}
```
public ImageSignature(String signatureId)
```


検索プロセス後に取得した署名識別子で ImageSignature オブジェクトを初期化します。
このユニークな識別子は、ドキュメント署名情報層からこのシグネチャの追加プロパティを検索するために使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatureId | java.lang.String | Signature クラスの Sign または Search メソッドで取得されたユニークな署名識別子 [Signature](../../com.groupdocs.signature/signature)。 |
|

### ImageSignature() {#ImageSignature--}
```
public ImageSignature()
```


デフォルトパラメーターで ImageSignature を初期化します。


### getSize() {#getSize--}
```
public final int getSize()
```


署名画像のサイズ（バイト単位）を指定します。


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


署名画像のサイズ（バイト単位）を指定します。



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


署名画像の形式を指定します。


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFormat(FileType value) {#setFormat-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFormat(FileType value)
```


署名画像の形式を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### getContent() {#getContent--}
```
public final byte[] getContent()
```


タイプの画像バイナリデータ内容を指定します。
フォーマット
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
デフォルトではこのプロパティは設定されません。
プロパティを使用してください
ImageSearchOptions.ReturnContent
この機能を有効にするには ({ ImageSearchOptions#getReturnContent}/{ ImageSearchOptions#setReturnContent(boolean)}) を使用します。


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

