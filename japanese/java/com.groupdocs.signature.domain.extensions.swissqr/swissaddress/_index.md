---
title: "SwissAddress"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "債権者または債務者の住所を表します。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

債権者または債務者の住所を表します。
ストリート、番地、郵便番号、町（構造化住所タイプ）を設定するか、
または住所行1と2（結合住所要素タイプ）を設定できます。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 名前を取得または設定します。自然人の姓と名、または |
法人の会社名。
|
|  | [setName(String value)](#setName-java.lang.String-) | 名前を取得または設定します。自然人の姓と名、または |
法人の会社名。
|
|  | [getAddressLine1()](#getAddressLine1--) | 住所行1 を取得または設定します。 |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 住所行1 を取得または設定します。 |
|
|  | [getAddressLine2()](#getAddressLine2--) | 住所行2 を取得または設定します。 |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 住所行2 を取得または設定します。 |
|
|  | [getStreet()](#getStreet--) | 通り を取得または設定します。 |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | 通り を取得または設定します。 |
|
|  | [getHouseNo()](#getHouseNo--) | 番地 を取得または設定します。 |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 番地 を取得または設定します。 |
|
|  | [getPostalCode()](#getPostalCode--) | 郵便番号 を取得または設定します。 |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 郵便番号 を取得または設定します。 |
|
|  | [getTown()](#getTown--) | 町または市 を取得または設定します。 |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | 町または市 を取得または設定します。 |
|
|  | [getCountryCode()](#getCountryCode--) | 2文字の ISO 国コード を取得または設定します。 |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 2文字の ISO 国コード を取得または設定します。 |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


名前を取得または設定します。自然人の姓と名、または
法人の会社名。
値: 名前。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


名前を取得または設定します。自然人の姓と名、または
法人の会社名。
値: 名前。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


住所行1 を取得または設定します。
住所行1 には通り名、番地、または私書箱が含まれます。
このフィールドは結合要素の住所でのみ使用され、オプションです。
値: 住所行1。


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


住所行1 を取得または設定します。
住所行1 には通り名、番地、または私書箱が含まれます。
このフィールドは結合要素の住所でのみ使用され、オプションです。
値: 住所行1。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


住所行2 を取得または設定します。
住所行2 には郵便番号と町が含まれます。
このフィールドは結合要素の住所でのみ使用されます。このタイプでは必須です。
値: 住所行2。


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


住所行2 を取得または設定します。
住所行2 には郵便番号と町が含まれます。
このフィールドは結合要素の住所でのみ使用されます。このタイプでは必須です。
値: 住所行2。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


通り を取得または設定します。
通りは番地なしで指定する必要があります。
このフィールドは構造化住所でのみ使用され、オプションです。
値: 通り。


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


通り を取得または設定します。
通りは番地なしで指定する必要があります。
このフィールドは構造化住所でのみ使用され、オプションです。
値: 通り。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


番地 を取得または設定します。
このフィールドは構造化住所でのみ使用され、オプションです。
値: 番地。


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


番地 を取得または設定します。
このフィールドは構造化住所でのみ使用され、オプションです。
値: 番地。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


郵便番号 を取得または設定します。
このフィールドは構造化住所でのみ使用されます。このタイプでは必須です。
値: 郵便番号。


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


郵便番号 を取得または設定します。
このフィールドは構造化住所でのみ使用されます。このタイプでは必須です。
値: 郵便番号。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


町または市 を取得または設定します。
このフィールドは構造化住所でのみ使用されます。このタイプでは必須です。
値: 町または市。


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


町または市 を取得または設定します。
このフィールドは構造化住所でのみ使用されます。このタイプでは必須です。
値: 町または市。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


2文字の ISO 国コード を取得または設定します。
住所全体が null または空の値を含む場合を除き、国コードは必須です。
値: ISO 国コード。


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


2文字の ISO 国コード を取得または設定します。
住所全体が null または空の値を含む場合を除き、国コードは必須です。
値: ISO 国コード。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

