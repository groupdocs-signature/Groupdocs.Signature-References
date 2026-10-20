---
title: "CryptoCurrencyTransfer"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "Crypto 通貨転送の受取人または QR コード用転送を表します。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

QRコード用の暗号通貨転送（受取人または送金）を表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getType()](#getType--) | サポートされている暗号通貨タイプのいずれかを取得または設定します。 |
|
|  | [setType(int value)](#setType-int-) | サポートされている暗号通貨タイプのいずれかを取得または設定します。 |
|
|  | [getAmount()](#getAmount--) | 転送金額を取得または設定します。 |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | 転送金額を取得または設定します。 |
|
|  | [getAddress()](#getAddress--) | 暗号通貨の公開アドレスを取得または設定します。 |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | 暗号通貨の公開アドレスを取得または設定します。 |
|
|  | [getMessage()](#getMessage--) | オプションの転送メッセージを取得または設定します。 |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | オプションの転送メッセージを取得または設定します。 |
|
|  | [getCustomType()](#getCustomType--) | オプションの転送メッセージを取得または設定します。 |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | オプションの転送メッセージを取得または設定します。 |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Crypto 通貨転送プロパティを比較するために Equals メソッドをオーバーライドします |
|
|  | [hashCode()](#hashCode--) | GetHashCodeメソッドをオーバーライドします。 |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


サポートされている暗号通貨タイプのいずれかを取得または設定します。


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


サポートされている暗号通貨タイプのいずれかを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


転送金額を取得または設定します。


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


転送金額を取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


暗号通貨の公開アドレスを取得または設定します。


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


暗号通貨の公開アドレスを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


オプションの転送メッセージを取得または設定します。


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


オプションの転送メッセージを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


オプションの転送メッセージを取得または設定します。


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


オプションの転送メッセージを取得または設定します。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Crypto 通貨転送プロパティを比較するために Equals メソッドをオーバーライドします


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
|  | obj | java.lang.Object | 比較対象となる Crypto 通貨転送オブジェクト。 |
|

**Returns:**
boolean - 渡された Crypto 通貨転送オブジェクトが同じ型で、すべてのプロパティがこのインスタンスのプロパティと等しい場合に true を返します。

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCodeメソッドをオーバーライドします。


**Returns:**
int - Crypto 通貨転送のハッシュコード

