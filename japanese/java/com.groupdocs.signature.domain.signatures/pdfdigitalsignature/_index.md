---
title: "PdfDigitalSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "PDF デジタル署名のプロパティを含みます。"
type: docs
weight: 15
url: /ja/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

PDF デジタル署名のプロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | 証明書なしで Pdf Digital Signature を初期化します。 |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | 指定された証明書で Pdf Digital signature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | 署名者が受取人に連絡できるように提供する情報 |
署名を検証するために、例として
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | 署名者が受取人に連絡できるように提供する情報 |
署名を検証するために、例として
|
|  | [getLocation()](#getLocation--) | 署名の CPU ホスト名または物理的な場所です。 |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 署名の CPU ホスト名または物理的な場所です。 |
|
|  | [getReason()](#getReason--) | 署名の理由、例として (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦)。 |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 署名の理由、例として (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦)。 |
|
|  | [getType()](#getType--) | Pdf デジタル署名のタイプです。 |
|
|  | [setType(int value)](#setType-int-) | Pdf デジタル署名のタイプです。 |
|
|  | [getTimeStamp()](#getTimeStamp--) | Pdf デジタル署名のタイムスタンプです。 |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Pdf デジタル署名のタイムスタンプです。 |
|
|  | [getShowProperties()](#getShowProperties--) | 署名プロパティの表示/非表示を強制します。 |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | 署名プロパティの表示/非表示を強制します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Barcode Signature インスタンスをクローンします。 |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


証明書なしで Pdf Digital Signature を初期化します。


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


指定された証明書で Pdf Digital signature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 証明書 | java.security.KeyStore | X509 証明書です。 |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


署名者が受取人に連絡できるように提供する情報
署名を検証するために、例として電話番号を使用します。


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


署名者が受取人に連絡できるように提供する情報
署名を検証するために、例として電話番号を使用します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


署名の CPU ホスト名または物理的な場所です。


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


署名の CPU ホスト名または物理的な場所です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


署名の理由、例として (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦)。


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


署名の理由、例として (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦)。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Pdf デジタル署名のタイプです。


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Pdf デジタル署名のタイプです。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Pdf デジタル署名のタイムスタンプです。
デフォルト値は null です。


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Pdf デジタル署名のタイムスタンプです。
デフォルト値は null です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名
フィールドは外観の事前定義された形式を持ちます
デジタル署名者 {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} 日付: {Date} 理由: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
場所: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties はデフォルトで true です。


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


署名プロパティの表示/非表示を強制します。ShowProperties が true の場合、署名
フィールドは外観の事前定義された形式を持ちます
デジタル署名者 {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} 日付: {Date} 理由: {
Reason
(#getReason.getReason/#setReason(String).setReason(String))}
場所: {
Location
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties はデフォルトで true です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | boolean |  |

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

