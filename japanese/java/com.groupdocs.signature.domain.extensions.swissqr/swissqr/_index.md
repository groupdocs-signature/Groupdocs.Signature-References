---
title: "SwissQR"
second_title: "Java 用 GroupDocs.Signature API リファレンス"
description: "SwissQR コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。"
type: docs
weight: 11
url: /ja/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

SwissQR コードに埋め込まれたテキストのエンコードとデコードを行うクラスです。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | SwissQR のインスタンスを作成します。 |
|
## メソッド

| メソッド | 説明 |
| --- | --- |
|  | [getAmount()](#getAmount--) | 支払金額を取得または設定します。 |
|
|  | [setAmount(double value)](#setAmount-double-) | 支払金額を取得または設定します。 |
|
|  | [getCurrency()](#getCurrency--) | 支払通貨を取得または設定します。 |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | 支払通貨を取得または設定します。 |
|
|  | [getAccount()](#getAccount--) | 債権者の口座番号を取得または設定します。 |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | 債権者の口座番号を取得または設定します。 |
|
|  | [getCreditor()](#getCreditor--) | 債権者の住所を取得または設定します。 |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 債権者の住所を取得または設定します。 |
|
|  | [getReference()](#getReference--) | 債権者の支払参照を取得または設定します。 |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 債権者の支払参照を取得または設定します。 |
|
|  | [getDebtor()](#getDebtor--) | 債務者の住所を取得または設定します。 |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 債務者の住所を取得または設定します。 |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | 追加の非構造化メッセージを取得または設定します。 |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 追加の非構造化メッセージを取得または設定します。 |
|
|  | [getBillInformation()](#getBillInformation--) | 追加の構造化請求情報を取得または設定します。 |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 追加の構造化請求情報を取得または設定します。 |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


SwissQR のインスタンスを作成します。


### getAmount() {#getAmount--}
```
public final double getAmount()
```


支払金額を取得または設定します。
有効な値は0.01から999,999,999.99の間です。
値: 支払金額。


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


支払金額を取得または設定します。
有効な値は0.01から999,999,999.99の間です。
値: 支払金額。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


支払通貨を取得または設定します。
有効な値は"CHF"と"EUR"です。
値: 支払通貨。


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


支払通貨を取得または設定します。
有効な値は"CHF"と"EUR"です。
値: 支払通貨。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


債権者の口座番号を取得または設定します。
口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。
口座番号にはスペースを含めることができます。
値: 債権者の口座番号。


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


債権者の口座番号を取得または設定します。
口座番号はスイスまたはリヒテンシュタインの銀行の有効なIBANである必要があります。
口座番号にはスペースを含めることができます。
値: 債権者の口座番号。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


債権者の住所を取得または設定します。
値: 債権者の住所。


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


債権者の住所を取得または設定します。
値: 債権者の住所。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


債権者の支払参照を取得または設定します。
SwissQR IBAN、すなわち CHxx30000xxxxxx の範囲の IBAN では、参照は必須です。
CHxx31999xxxxx まで。
指定する場合、参照は有効な SwissQR 参照（対応する
ISR 参照形式）または ISO 11649（"RFxxxx"）に基づく有効な債権者参照のいずれかでなければなりません。
どちらも書式設定のためにスペースを含めることができます。
値: 債権者の支払参照。


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


債権者の支払参照を取得または設定します。
SwissQR IBAN、すなわち CHxx30000xxxxxx の範囲の IBAN では、参照は必須です。
CHxx31999xxxxx まで。
指定する場合、参照は有効な SwissQR 参照（対応する
ISR 参照形式）または ISO 11649（"RFxxxx"）に基づく有効な債権者参照のいずれかでなければなりません。
どちらも書式設定のためにスペースを含めることができます。
値: 債権者の支払参照。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


債務者の住所を取得または設定します。
債務者は任意です。省略した場合、このフィールドを null に設定するか、
すべて null または空の値の住所を設定しても問題ありません。
値: 債務者の住所。


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


債務者の住所を取得または設定します。
債務者は任意です。省略した場合、このフィールドを null に設定するか、
すべて null または空の値の住所を設定しても問題ありません。
値: 債務者の住所。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


追加の非構造化メッセージを取得または設定します。
値: 非構造化メッセージ。


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


追加の非構造化メッセージを取得または設定します。
値: 非構造化メッセージ。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


追加の構造化請求情報を取得または設定します。
値: 構造化請求情報。


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


追加の構造化請求情報を取得または設定します。
値: 構造化請求情報。


**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| 値 | java.lang.String |  |

