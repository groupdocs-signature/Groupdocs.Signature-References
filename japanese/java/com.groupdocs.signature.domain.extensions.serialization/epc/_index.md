---
title: "EPC"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "欧州支払委員会のクイックレスポンスコードを表します。"
type: docs
weight: 14
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

欧州支払委員会のクイックレスポンスコードを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [EPC()](#EPC--) | 新しい EPC オブジェクトをインスタンス化します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getName()](#getName--) | 受取人の名前を取得または設定します。 |
|
|  | [setName(String value)](#setName-java.lang.String-) | 受取人の名前を取得または設定します。 |
|
|  | [getBIC()](#getBIC--) | 受取人の BIC を最大 11 文字の長さで取得または設定します。 |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | 受取人の BIC を最大 11 文字の長さで取得または設定します。 |
|
|  | [getIBAN()](#getIBAN--) | 受取人の口座 (IBAN) を取得または設定します。 |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | 受取人の口座 (IBAN) を取得または設定します。 |
|
|  | [getAmount()](#getAmount--) | 金額を取得または設定します。 |
|
|  | [setAmount(double value)](#setAmount-double-) | 金額を取得または設定します。 |
|
|  | [getCode()](#getCode--) | 最大 4 文字のビジネスコードを取得または設定します。 |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | 最大 4 文字のビジネスコードを取得または設定します。 |
|
|  | [getReference()](#getReference--) | 支払参照 (最大 35 文字) を取得または設定します。 |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 支払参照 (最大 35 文字) を取得または設定します。 |
|
|  | [getRemittance()](#getRemittance--) | 送金情報 (最大 140 文字) を取得または設定します。 |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | 送金情報 (最大 140 文字) を取得または設定します。 |
|
|  | [getInformation()](#getInformation--) | ヒント情報を取得または設定します。 |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | ヒント情報を取得または設定します。 |
|
|  | [getVersion()](#getVersion--) | EPC / SEPA QRコード バージョンの実装。 |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QRコード バージョンの実装。 |
|
|  | [getCharset()](#getCharset--) | EPC / SEPA QRコード 文字セットの実装。 |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QRコード 文字セットの実装。 |
|
|  | [getIdentification()](#getIdentification--) | EPC / SEPA QRコード の識別。 |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QRコード の識別。 |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | EPC プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### EPC() {#EPC--}
```
public EPC()
```


新しい EPC オブジェクトをインスタンス化します。


### getName() {#getName--}
```
public final String getName()
```


受取人の名前を取得または設定します。最大長は 70 文字です。


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


受取人の名前を取得または設定します。最大長は 70 文字です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


受取人の BIC を最大 11 文字の長さで取得または設定します。


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


受取人の BIC を最大 11 文字の長さで取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


受取人の口座（IBAN）を取得または設定します。IBAN は最大 34 文字の英数字で構成されます。


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


受取人の口座（IBAN）を取得または設定します。IBAN は最大 34 文字の英数字で構成されます。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


金額を取得または設定します。


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


金額を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


最大 4 文字のビジネスコードを取得または設定します。


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


最大 4 文字のビジネスコードを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


支払参照（最大 35 文字）を取得または設定します。このフィールドと送金情報フィールドは相互に排他的です。


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


支払参照（最大 35 文字）を取得または設定します。このフィールドと送金情報フィールドは相互に排他的です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


送金情報（最大 140 文字）を取得または設定します。このフィールドと支払参照フィールドは相互に排他的です。


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


送金情報（最大 140 文字）を取得または設定します。このフィールドと支払参照フィールドは相互に排他的です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


ヒント情報を取得または設定します。最大 70 文字です。


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


ヒント情報を取得または設定します。最大 70 文字です。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR コード バージョンの実装です。デフォルトではこの値は 002 に設定されています。


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR コード バージョンの実装です。デフォルトではこの値は 002 に設定されています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR コード 文字セットの実装です。デフォルトではこの値は 1 に設定されています。


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR コード 文字セットの実装です。デフォルトではこの値は 1 に設定されています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR コード の識別です。デフォルトではこの値は SCT に設定されています。


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR コード の識別です。デフォルトではこの値は SCT に設定されています。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


EPC プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | ソース | java.lang.Object | 比較対象となる EPC オブジェクトです。 |
|

**Returns:**
boolean - 渡されたアドレスオブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Email のハッシュコード

