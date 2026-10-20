---
title: "MetadataSignOptions"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "メタデータ署名オプションを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.options.sign/metadatasignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)
```
public class MetadataSignOptions extends SignOptions
```

メタデータ署名オプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [MetadataSignOptions()](#MetadataSignOptions--) | デフォルト値で SignMetadataOptions クラスの新しいインスタンスを初期化します。 |
|
|  | [MetadataSignOptions(ArrayList<MetadataSignature> signatures)](#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--) | Metadata を使用して SignMetadataOptions クラスの新しいインスタンスを初期化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getSignatures()](#getSignatures--) | 署名のメタデータを取得または設定します。 |
|
|  | [setSignatures(MetadataSignatureCollection value)](#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-) | 署名のメタデータを取得または設定します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [addPdfSignature(String name, Object value, String tag)](#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-) | 渡された引数で新しい PdfMetadataSignature を作成し、コレクションに追加します。 |
|
|  | [addImageSignature(int id, Object value)](#addImageSignature-int-java.lang.Object-) | 渡された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。 |
|
|  | [add(MetadataSignature metadataSignature)](#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-) | 既存の MetadataSignature インスタンスをコレクションに追加します。 |
|
|  | [validate()](#validate--) | オプションパラメータを検証する内部メソッドです。 |
|
|  | [toString()](#toString--) | 文字列変換をオーバーライドします。 |
|
| [signature()](#signature--) |  |
### MetadataSignOptions() {#MetadataSignOptions--}
```
public MetadataSignOptions()
```


デフォルト値で SignMetadataOptions クラスの新しいインスタンスを初期化します。


### MetadataSignOptions(ArrayList<MetadataSignature> signatures) {#MetadataSignOptions-java.util.ArrayList-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature--}
```
public MetadataSignOptions(ArrayList<MetadataSignature> signatures)
```


Metadata を使用して SignMetadataOptions クラスの新しいインスタンスを初期化します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | signatures | java.util.ArrayList<com.groupdocs.signature.domain.signatures.metadata.MetadataSignature> | Metadata 署名のコレクション [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)。 |
|

### getSignatures() {#getSignatures--}
```
public final MetadataSignatureCollection getSignatures()
```


署名のメタデータを取得または設定します。


**Returns:**
[MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection)
### setSignatures(MetadataSignatureCollection value) {#setSignatures-com.groupdocs.signature.domain.signatures.metadata.MetadataSignatureCollection-}
```
public final void setSignatures(MetadataSignatureCollection value)
```


署名のメタデータを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [MetadataSignatureCollection](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignaturecollection) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QRコード署名テキストまたはデータプロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### addPdfSignature(String name, Object value, String tag) {#addPdfSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public final PdfMetadataSignature addPdfSignature(String name, Object value, String tag)
```


渡された引数で新しい PdfMetadataSignature を作成し、コレクションに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Metadata 署名オブジェクトの名前 |
|
|  | 値 | java.lang.Object | メタデータ署名の値 |
|
|  | タグ | java.lang.String | メタデータ署名のプレフィックスタグ |
|

**Returns:**
[PdfMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### addImageSignature(int id, Object value) {#addImageSignature-int-java.lang.Object-}
```
public final ImageMetadataSignature addImageSignature(int id, Object value)
```


渡された引数で新しい ImageMetadataSignature を作成し、コレクションに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ID | int | 画像メタデータ署名名の一意の識別子です。可能な ID 値については、Exif タグ仕様の参照をご覧ください |
|
|  | 値 | java.lang.Object | メタデータの値 |
|

**Returns:**
[ImageMetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature) - Newly created signature that was added to MetadataSignatures collection

### add(MetadataSignature metadataSignature) {#add-com.groupdocs.signature.domain.signatures.metadata.MetadataSignature-}
```
public final MetadataSignOptions add(MetadataSignature metadataSignature)
```


既存の MetadataSignature インスタンスをコレクションに追加します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | metadataSignature | [MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) | 追加する既存の MetadataSignature インスタンス |
|

**Returns:**
[MetadataSignOptions](../../com.groupdocs.signature.options.sign/metadatasignoptions) - Instance itself

### validate() {#validate--}
```
public void validate()
```


オプションパラメータを検証する内部メソッドです。


### toString() {#toString--}
```
public String toString()
```


文字列変換をオーバーライドします。


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
