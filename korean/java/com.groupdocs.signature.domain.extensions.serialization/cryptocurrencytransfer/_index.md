---
title: "CryptoCurrencyTransfer"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "암호화폐 전송 수신자 또는 QR 코드 전송을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/cryptocurrencytransfer/
---
**Inheritance:**
java.lang.Object
```
public class CryptoCurrencyTransfer
```

QR 코드용 암호화폐 전송(수신자 또는 전송)을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [CryptoCurrencyTransfer()](#CryptoCurrencyTransfer--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getType()](#getType--) | 지원되는 암호화폐 유형 중 하나를 가져오거나 설정합니다. |
|
|  | [setType(int value)](#setType-int-) | 지원되는 암호화폐 유형 중 하나를 가져오거나 설정합니다. |
|
|  | [getAmount()](#getAmount--) | 전송 금액을 가져오거나 설정합니다. |
|
|  | [setAmount(BigDecimal value)](#setAmount-java.math.BigDecimal-) | 전송 금액을 가져오거나 설정합니다. |
|
|  | [getAddress()](#getAddress--) | 암호화폐 공개 주소를 가져오거나 설정합니다. |
|
|  | [setAddress(String value)](#setAddress-java.lang.String-) | 암호화폐 공개 주소를 가져오거나 설정합니다. |
|
|  | [getMessage()](#getMessage--) | 선택적 전송 메시지를 가져오거나 설정합니다. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | 선택적 전송 메시지를 가져오거나 설정합니다. |
|
|  | [getCustomType()](#getCustomType--) | 선택적 전송 메시지를 가져오거나 설정합니다. |
|
|  | [setCustomType(String value)](#setCustomType-java.lang.String-) | 선택적 전송 메시지를 가져오거나 설정합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | 암호화폐 전송 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
### CryptoCurrencyTransfer() {#CryptoCurrencyTransfer--}
```
public CryptoCurrencyTransfer()
```


### getType() {#getType--}
```
public final int getType()
```


지원되는 암호화폐 유형 중 하나를 가져오거나 설정합니다.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


지원되는 암호화폐 유형 중 하나를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getAmount() {#getAmount--}
```
public final BigDecimal getAmount()
```


전송 금액을 가져오거나 설정합니다.


**Returns:**
java.math.BigDecimal
### setAmount(BigDecimal value) {#setAmount-java.math.BigDecimal-}
```
public final void setAmount(BigDecimal value)
```


전송 금액을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.math.BigDecimal |  |

### getAddress() {#getAddress--}
```
public final String getAddress()
```


암호화폐 공개 주소를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setAddress(String value) {#setAddress-java.lang.String-}
```
public final void setAddress(String value)
```


암호화폐 공개 주소를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


선택적 전송 메시지를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


선택적 전송 메시지를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCustomType() {#getCustomType--}
```
public final String getCustomType()
```


선택적 전송 메시지를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setCustomType(String value) {#setCustomType-java.lang.String-}
```
public final void setCustomType(String value)
```


선택적 전송 메시지를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


암호화폐 전송 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 객체 | java.lang.Object | 비교할 암호화폐 전송 객체. |
|

**Returns:**
boolean - 전달된 암호화폐 전송 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - 암호화폐 전송 해시 코드

