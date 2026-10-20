---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）の二次および追加データを格納するクラス。"
type: docs
weight: 13
url: /ja/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

HIBC（Healthcare Industry Bar Code Council）LIC（Licensed Identification Code）の二次および追加データを格納するクラス。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | 既定 ctor() |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | 有効期限の日付形式を識別します。 |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | 有効期限の日付形式を識別します。 |
|
|  | [getExpiryDate()](#getExpiryDate--) | 有効期限を識別します。 |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | 有効期限を識別します。 |
|
|  | [getLotNumber()](#getLotNumber--) | ロットまたはバッチ番号を識別します。 |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | ロットまたはバッチ番号を識別します。 |
|
|  | [getSerialNumber()](#getSerialNumber--) | シリアル番号を識別します。 |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | シリアル番号を識別します。 |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | 製造日を識別します。 |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | 製造日を識別します。 |
|
|  | [getQuantity()](#getQuantity--) | 数量を識別します。数量は0から500までの整数である必要があります。 |
|
|  | [setQuantity(int value)](#setQuantity-int-) | 数量を識別します。数量は0から500までの整数である必要があります。 |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | 出力文字列内のリンク文字を識別します。 |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | 出力文字列内のリンク文字を識別します。 |
|
|  | [deepClone()](#deepClone--) | このオブジェクトのコピーを取得します。 |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


既定 ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


有効期限の日付形式を識別します。


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


有効期限の日付形式を識別します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


有効期限を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


有効期限を識別します。ExpiryDateFormat が None に設定されていない場合に使用されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


ロットまたはバッチ番号を識別します。
ロット/バッチ番号は最大18文字の英数字文字列である必要があります。


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


ロットまたはバッチ番号を識別します。
ロット/バッチ番号は最大18文字の英数字文字列である必要があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


シリアル番号を識別します。
シリアル番号は最大18文字の英数字文字列である必要があります。


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


シリアル番号を識別します。
シリアル番号は最大18文字の英数字文字列である必要があります。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


製造日を識別します。
このフィールドを使用しない場合は、製造日を DateTime.MinValue に設定できます。
デフォルト値: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


製造日を識別します。
このフィールドを使用しない場合は、製造日を DateTime.MinValue に設定できます。
デフォルト値: DateTime.MinValue


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


数量を識別します。数量は0から500までの整数である必要があります。
このフィールドを使用しない場合は、数量を -1 に設定できます。デフォルト値: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


数量を識別します。数量は0から500までの整数である必要があります。
このフィールドを使用しない場合は、数量を -1 に設定できます。デフォルト値: -1


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


出力文字列内のリンク文字を識別します。


**Returns:**
char
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


出力文字列内のリンク文字を識別します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | char |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


このオブジェクトのコピーを取得します。


**Returns:**
java.lang.Object
