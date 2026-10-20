---
title: "MetadataSignature"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "メタデータ署名プロパティを含みます。"
type: docs
weight: 12
url: /ja/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

メタデータ署名プロパティを含みます。

## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 一意のメタデータ名を指定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 一意のメタデータ名を指定します。 |
|
|  | [getValue()](#getValue--) | メタデータ オブジェクトを指定します。 |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | メタデータ オブジェクトを指定します。 |
|
|  | [getType()](#getType--) | メタデータ 値の型を指定します。 |
|
|  | [setType(int value)](#setType-int-) | メタデータ 値の型を指定します。 |
|
|  | [getDataEncryption()](#getDataEncryption--) | 署名の Value プロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 署名の Value プロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。 |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | デシリアライズ時にメタデータ署名 Value からオブジェクトを取得します。 |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | デシリアライズ時にメタデータ署名 Text からオブジェクトを取得します。 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 署名プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
|  | [toBoolean()](#toBoolean--) | ブール値に変換します。 |
|
|  | [toInteger()](#toInteger--) | 整数に変換します。 |
|
|  | [toDouble()](#toDouble--) | Double に変換します。 |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double に変換します。 |
|
|  | [toSingle()](#toSingle--) | float に変換します。 |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | float に変換します。 |
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
|  | [deepClone()](#deepClone--) | Metadata Signature インスタンスをクローンします。 |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 指定された値でメタデータ署名インスタンスをクローンします。 |
|
### getName() {#getName--}
```
public final String getName()
```


一意のメタデータ名を指定します。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


一意のメタデータ名を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


メタデータ オブジェクトを指定します。


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


メタデータ オブジェクトを指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


メタデータ 値の型を指定します。


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


メタデータ 値の型を指定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


署名の Value プロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


署名の Value プロパティをエンコードおよびデコードするための [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) インターフェイスの実装を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


デシリアライズ時にメタデータ署名 Value からオブジェクトを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - T オブジェクトのインスタンス


T
: メタデータ値からデシリアライズするオブジェクトの型

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


デシリアライズ時にメタデータ署名 Text からオブジェクトを取得します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | カスタムデータ暗号化実装を設定する |


T
: メタデータ値からデシリアライズするオブジェクトの型
|

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


### toDouble() {#toDouble--}
```
public double toDouble()
```


Double に変換します。


**Returns:**
double - Metadata Signature の値を Double として返します。

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

### toSingle() {#toSingle--}
```
public float toSingle()
```


float に変換します。


**Returns:**
float - Metadata Signature の値を float として返します。

<br />

*** ** * ** ***

Metadata の値を変換できない場合、例外をスローします。元の値が文字列ベースの場合、SignatureSettings のプロパティ SignatureSettings.DefaultCulture () から既定のカルチャ情報が使用されます。

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
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

<br />

*** ** * ** ***

ブール型プロパティを "True" または "False" に変換します。別のデータ型の場合、既定のデータ形式プロバイダーが使用されます。

<br />


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


指定された値でメタデータ署名インスタンスをクローンします。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | 値 | java.lang.Object | 新しいクローンオブジェクトの値です。 |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

