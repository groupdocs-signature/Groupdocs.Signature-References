---
title: "ImageMetadataSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "画像メタデータ署名プロパティを含みます。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

画像メタデータ署名プロパティを含みます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Id と値を指定して Image Metadata Signature を作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getId()](#getId--) | Image Metadata署名の識別子。 |
|
|  | [setId(int value)](#setId-int-) | Image Metadata署名の識別子。 |
|
|  | [getSize()](#getSize--) | Metadata値のサイズを取得するための読み取り専用値 |
|
|  | [setSize(int value)](#setSize-int-) | Metadata値のサイズを取得するための読み取り専用値 |
|
|  | [getDescription()](#getDescription--) | 標準のImage Metadata署名の説明を取得するための読み取り専用値 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [deepClone()](#deepClone--) | Metadata Signature インスタンスをクローンします。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 指定された値でImage Metadata Signatureインスタンスをクローンします。 |
|
|  | [toBoolean()](#toBoolean--) | ブール値に変換します。 |
|
|  | [toInteger()](#toInteger--) | 整数に変換します。 |
|
|  | [toLong()](#toLong--) | longに変換します。 |
|
|  | [toSingle()](#toSingle--) | float に変換します。 |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | float に変換します。 |
|
|  | [toDouble()](#toDouble--) | Double に変換します。 |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double に変換します。 |
|
|  | [toDecimal()](#toDecimal--) | Decimalに変換します。 |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Decimalに変換します。 |
|
|  | [toDateTime()](#toDateTime--) | DateTime に変換します。 |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | DateTime に変換します。 |
|
|  | [toString()](#toString--) | ToString() メソッドをオーバーライドして文字列に変換します |
|
|  | [toString(String format)](#toString-java.lang.String-) | 指定された形式で文字列に変換します |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | 指定された形式で文字列に変換します |
|
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Id と値を指定して Image Metadata Signature を作成します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ID | int | 画像メタデータ署名名の一意の識別子です。可能な ID 値については、Exif タグ仕様の参照をご覧ください |
|
|  | 値 | java.lang.Object | メタデータの値 |
|

### getId() {#getId--}
```
public final int getId()
```


Image Metadata署名の識別子。
標準のSignatureを事前定義されたId値で含む[ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures)クラスをご覧ください。


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Image Metadata署名の識別子。
標準のSignatureを事前定義されたId値で含む[ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures)クラスをご覧ください。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


Metadata値のサイズを取得するための読み取り専用値


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


Metadata値のサイズを取得するための読み取り専用値


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


標準のImage Metadata署名の説明を取得するための読み取り専用値


**Returns:**
java.lang.String
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


指定された値でImage Metadata Signatureインスタンスをクローンします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | 新しいクローンオブジェクトの値です。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


ブール値に変換します。


**Returns:**
boolean - メタデータ署名値をブール値として返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


整数に変換します。


**Returns:**
int - Metadata Signature の値を整数として返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />


### toLong() {#toLong--}
```
public final long toLong()
```


longに変換します。


**Returns:**
long - Metadata Signatureの値をlongとして返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


float に変換します。


**Returns:**
float - Image Metadata Signatureの値をfloatとして返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。元の値が文字列ベースの場合、SignatureSettings のプロパティ SignatureSettings.DefaultCulture から既定のカルチャ情報が使用されます。

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
```


float に変換します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | プロバイダー | java.util.Locale | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />

|

**Returns:**
float - Metadata Signature の値を float として返します。

### toDouble() {#toDouble--}
```
public double toDouble()
```


Double に変換します。


**Returns:**
double - Image Metadata Signatureの値をDoubleとして返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。元の値が文字列ベースの場合、SignatureSettings のプロパティ SignatureSettings.DefaultCulture から既定のカルチャ情報が使用されます。

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Double に変換します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | プロバイダー | java.util.Locale | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />

|

**Returns:**
double - Metadata Signature の値を Double として返します。

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Decimalに変換します。


**Returns:**
java.math.BigDecimal - Image Metadata Signatureの値をDecimalとして返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。元の値が文字列ベースの場合、SignatureSettings のプロパティ SignatureSettings.DefaultCulture から既定のカルチャ情報が使用されます。

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Decimalに変換します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | プロバイダー | java.util.Locale | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />

|

**Returns:**
java.math.BigDecimal - Metadata Signatureの値をDecimalとして返します。

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


DateTime に変換します。


**Returns:**
java.util.Date - Metadata Signature の値を DateTime として返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。元の値が文字列ベースの場合、SignatureSettings のプロパティ SignatureSettings.DefaultCulture から既定のカルチャ情報が使用されます。

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


DateTime に変換します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | プロバイダー | java.util.Locale | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。

<br />

|

**Returns:**
java.util.Date - Metadata Signature の値を DateTime として返します。

### toString() {#toString--}
```
public String toString()
```


ToString() メソッドをオーバーライドして文字列に変換します


**Returns:**
java.lang.String - Metadata Signature の値を String として返します。

### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


指定された形式で文字列に変換します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | フォーマット | java.lang.String | データ形式文字列。 |

<br />

*** ** * ** ***

ブール型プロパティを "True" または "False" に変換します。SignatureSettings のプロパティ SignatureSettings.DefaultCulture から既定のカルチャ情報が使用されます。

<br />

|

**Returns:**
java.lang.String - Metadata Signature の値を String として返します。

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


指定された形式で文字列に変換します


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | フォーマット | java.lang.String | データ形式文字列。 |
|
|  | プロバイダー | java.util.Locale | データ変換操作で使用するデータプロバイダーをフォーマットします。 |

<br />

*** ** * ** ***

ブール型プロパティを "True" または "False" に変換します。

<br />

|

**Returns:**
java.lang.String - Metadata Signature の値を String として返します。

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

