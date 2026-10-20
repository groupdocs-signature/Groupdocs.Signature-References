---
title: "Mailmark2D"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "Royal Mail 2D Mailmark に埋め込まれたテキストをエンコードおよびデコードするクラス。"
type: docs
weight: 10
url: /ja/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Royal Mail 2D Mailmark に埋め込まれたテキストをエンコードおよびデコードするクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | デフォルトの一次および二次データ値を使用して、Royal Mail Mailmark の結合データを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | UPU 国コードを識別します。最大長さ: 4 文字。 |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU 国コードを識別します。最大長さ: 4 文字。 |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | 各製品タイプの Royal Mail Mailmark バーコードペイロードを識別します。 |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | 各製品タイプの Royal Mail Mailmark バーコードペイロードを識別します。 |
|
|  | [getVersionID()](#getVersionID--) | 各情報タイプ ID に関連するバーコードバージョンを識別します。 |
|
|  | [getClass_()](#getClass---) | アイテムのクラスを識別します。 |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | アイテムのクラスを識別します。 |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | 郵送に関与する顧客の固有グループを識別します。 |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | 郵送に関与する顧客の固有グループを識別します。 |
|
|  | [getItemID()](#getItemID--) | サプライチェーン ID 内の固有アイテムを識別します。 |
|
|  | [setItemID(int value)](#setItemID-int-) | サプライチェーン ID 内の固有アイテムを識別します。 |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | DPS を含む配送先住所の郵便番号が含まれます |
内陸の場合、郵便番号/DP は以下の文字数を含みます。
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | DPS を含む配送先住所の郵便番号が含まれます |
内陸の場合、郵便番号/DP は以下の文字数を含みます。
|
|  | [getRTSFlag()](#getRTSFlag--) | 要求されているリターン・トゥ・センダー（RTS）サービスのレベルを示すフラグです。 |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 要求されているリターン・トゥ・センダー（RTS）サービスのレベルを示すフラグです。 |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | リターン・トゥ・センダーの郵便番号が含まれますが、DPS はありません。 |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | リターン・トゥ・センダーの郵便番号が含まれますが、DPS はありません。 |
|
|  | [getCustomerContent()](#getCustomerContent--) | 顧客が使用できる任意のスペース。 |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | 顧客が使用できる任意のスペース。 |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | DataMatrix バーコードのエンコードモードです。 |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | DataMatrix バーコードのエンコードモードです。 |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


デフォルトの一次および二次データ値を使用して、Royal Mail Mailmark の結合データを作成します。


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


UPU 国コードを識別します。最大長さ: 4 文字。


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


UPU 国コードを識別します。最大長さ: 4 文字。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


各製品タイプの Royal Mail Mailmark バーコードペイロードを識別します。

<br />

*** ** * ** ***

有効な値: "0" - 国内の仕分け済みおよび未仕分け "A" - オンライン郵便料金 "B" - フランキング "C" - コンソリデーション

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


各製品タイプの Royal Mail Mailmark バーコードペイロードを識別します。

<br />

*** ** * ** ***

有効な値: "0" - 国内の仕分け済みおよび未仕分け "A" - オンライン郵便料金 "B" - フランキング "C" - コンソリデーション

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


各情報タイプ ID に関連するバーコードバージョンを識別します。

<br />

*** ** * ** ***

有効な値: "1" - 現在はこの値のみ使用 (デフォルト) "0" と "2" から "9"、"A" から "Z" は将来の使用のために予備として予約されています。

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


アイテムのクラスを識別します。

<br />

*** ** * ** ***

有効な値: "1" - 1C（小売） "2" - 2C（小売） "3" - エコノミー（小売） "5" - デフェード（小売） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス）

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


アイテムのクラスを識別します。

<br />

*** ** * ** ***

有効な値: "1" - 1C（小売） "2" - 2C（小売） "3" - エコノミー（小売） "5" - デフェード（小売） "8" - プレミアム（ネットワークアクセス） "9" - スタンダード（ネットワークアクセス）

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


郵送に関与する顧客の固有グループを識別します。
最大値: 9999999。


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


郵送に関与する顧客の固有グループを識別します。
最大値: 9999999。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


サプライチェーン ID 内の固有アイテムを識別します。
すべての Mailmark バーコードは、少なくとも 90 日間一意に識別できるように ID を持つ必要があります。
最大値: 99999999。


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


サプライチェーン ID 内の固有アイテムを識別します。
すべての Mailmark バーコードは、少なくとも 90 日間一意に識別できるように ID を持つ必要があります。
最大値: 99999999。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


DPS を含む配送先住所の郵便番号が含まれます
内陸の場合、郵便番号/DP は以下の文字数を含みます。
エリア (1 または 2 文字)
地区(1 または 2 文字)
セクター(1 文字)
ユニット(2 文字)
DPS (2 文字).
郵便番号と DPS は有効な PAF® フォーマットに準拠する必要があります。最大長は 9 です。


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


DPS を含む配送先住所の郵便番号が含まれます
内陸の場合、郵便番号/DP は以下の文字数を含みます。
エリア (1 または 2 文字)
地区(1 または 2 文字)
セクター(1 文字)
ユニット(2 文字)
DPS (2 文字).
郵便番号と DPS は有効な PAF® フォーマットに準拠する必要があります。最大長は 9 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


要求されている Return to Sender サービスのレベルを示すフラグ。最大長は 1 です。


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


要求されている Return to Sender サービスのレベルを示すフラグ。最大長は 1 です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


リターン・トゥ・センダーの郵便番号が含まれますが、DPS はありません。
PC（DPS なし）は PAF® フォーマットに準拠する必要があります。


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


リターン・トゥ・センダーの郵便番号が含まれますが、DPS はありません。
PC（DPS なし）は PAF® フォーマットに準拠する必要があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


顧客が使用できる任意のスペース。

<br />

*** ** * ** ***

タイプ別の最大長 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 文字 Type 9: 45 文字 Type 29: 25 文字

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


顧客が使用できる任意のスペース。

<br />

*** ** * ** ***

タイプ別の最大長 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): Type 7: 6 文字 Type 9: 45 文字 Type 29: 25 文字

<br />



**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


DataMatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.C40。 [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


DataMatrix バーコードのエンコードモード。デフォルト値: DataMatrixEncodeMode.C40。 [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark タイプは Data Matrix バーコードのサイズを定義します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


このオブジェクトのコピーを取得します。


**Returns:**
java.lang.Object
