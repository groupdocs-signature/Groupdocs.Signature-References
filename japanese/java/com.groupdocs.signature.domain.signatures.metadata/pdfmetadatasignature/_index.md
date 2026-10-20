---
title: "PdfMetadataSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDFメタデータ署名プロパティを含みます。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

PDFメタデータ署名プロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | 事前定義された名前と空の値で Pdf Metadata 署名を作成します |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | 事前定義された値で Pdf Metadata 署名を作成します |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | 事前定義された値で Pdf Metadata 署名を作成します |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Pdf Metadata 署名名のプレフィックスタグです。 |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf Metadata 署名名のプレフィックスタグです。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Metadata Signature インスタンスをクローンします。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 指定された値で Pdf Metadata Signature インスタンスをクローンします。 |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


事前定義された名前と空の値で Pdf Metadata 署名を作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Pdf Metadata 署名名 |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


事前定義された値で Pdf Metadata 署名を作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Metadata 署名オブジェクトの名前 |
|
|  | 値 | java.lang.Object | メタデータ署名の値 |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


事前定義された値で Pdf Metadata 署名を作成します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Metadata 署名オブジェクトの名前 |
|
|  | 値 | java.lang.Object | メタデータ署名の値 |
|
|  | タグ | java.lang.String | メタデータ署名のプレフィックスタグ |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf Metadata 署名名のプレフィックスタグです。デフォルトではこのプロパティは "xmp" に設定されています。
可能な値は次のとおりです


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf Metadata 署名名のプレフィックスタグです。デフォルトではこのプロパティは "xmp" に設定されています。
可能な値は次のとおりです


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

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


Metadata Signature インスタンスをクローンします。


**Returns:**
java.lang.Object - クローンされた Metadata Signature インスタンスを返します

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


指定された値で Pdf Metadata Signature インスタンスをクローンします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | 新しいクローンオブジェクトの値です。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

