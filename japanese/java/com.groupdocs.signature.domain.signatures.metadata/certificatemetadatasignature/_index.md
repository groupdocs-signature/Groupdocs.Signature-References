---
title: "CertificateMetadataSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "証明書メタデータ署名のプロパティを含みます。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.signatures.metadata/certificatemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class CertificateMetadataSignature extends MetadataSignature
```

証明書メタデータ署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [CertificateMetadataSignature(String name)](#CertificateMetadataSignature-java.lang.String-) | 事前定義された名前と空の値でCertificate Metadata Signatureを作成します。 |
|
|  | [CertificateMetadataSignature(String name, Object value)](#CertificateMetadataSignature-java.lang.String-java.lang.Object-) | 事前定義された値でCertificate Metadata Signatureを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [deepClone()](#deepClone--) | Metadata Signature インスタンスをクローンします。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 指定された値でCertificate Metadata Signatureインスタンスをクローンします。 |
|
|  | [toString()](#toString--) | ToString() メソッドをオーバーライドして文字列に変換します |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | 指定された形式で文字列に変換します |
|
### CertificateMetadataSignature(String name) {#CertificateMetadataSignature-java.lang.String-}
```
public CertificateMetadataSignature(String name)
```


事前定義された名前と空の値でCertificate Metadata Signatureを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Certificate Metadata Signatureの名前。 |
|

### CertificateMetadataSignature(String name, Object value) {#CertificateMetadataSignature-java.lang.String-java.lang.Object-}
```
public CertificateMetadataSignature(String name, Object value)
```


事前定義された値でCertificate Metadata Signatureを作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 名前 | java.lang.String | Metadata署名オブジェクトの名前。 |
|
|  | 値 | java.lang.Object | Metadata署名の値。 |
|

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


指定された値でCertificate Metadata Signatureインスタンスをクローンします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | 新しいクローンオブジェクトの値です。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toString() {#toString--}
```
public String toString()
```


ToString() メソッドをオーバーライドして文字列に変換します


**Returns:**
java.lang.String - Metadata Signature の値を String として返します。

<br />

*** ** * ** ***

ブール型プロパティを "True" または "False" に変換します。別のデータ型の場合、既定のデータ形式プロバイダーが使用されます。

<br />


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


指定された形式で文字列に変換します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | フォーマット | java.lang.String | データ形式文字列。 |
|
|  | プロバイダー | com.aspose.ms.System.IFormatProvider | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

ブール型プロパティを "True" または "False" に変換します。

<br />

|

**Returns:**
java.lang.String - Metadata Signature の値を String として返します。

