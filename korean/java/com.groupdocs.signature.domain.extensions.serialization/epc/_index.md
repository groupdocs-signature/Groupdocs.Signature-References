---
title: "EPC"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "European Payments Council QR 코드를 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/epc/
---
**Inheritance:**
java.lang.Object
```
public final class EPC
```

European Payments Council QR 코드를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [EPC()](#EPC--) | 새 EPC 객체를 인스턴스화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 수취인 이름을 가져오거나 설정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 수취인 이름을 가져오거나 설정합니다. |
|
|  | [getBIC()](#getBIC--) | 수취인 BIC를 최대 11자 길이로 가져오거나 설정합니다. |
|
|  | [setBIC(String value)](#setBIC-java.lang.String-) | 수취인 BIC를 최대 11자 길이로 가져오거나 설정합니다. |
|
|  | [getIBAN()](#getIBAN--) | 수취인 계좌(IBAN)를 가져오거나 설정합니다. |
|
|  | [setIBAN(String value)](#setIBAN-java.lang.String-) | 수취인 계좌(IBAN)를 가져오거나 설정합니다. |
|
|  | [getAmount()](#getAmount--) | 금액을 가져오거나 설정합니다. |
|
|  | [setAmount(double value)](#setAmount-double-) | 금액을 가져오거나 설정합니다. |
|
|  | [getCode()](#getCode--) | 비즈니스 코드를 최대 4자까지 가져오거나 설정합니다. |
|
|  | [setCode(String value)](#setCode-java.lang.String-) | 비즈니스 코드를 최대 4자까지 가져오거나 설정합니다. |
|
|  | [getReference()](#getReference--) | 결제 참조를 최대 35자까지 가져오거나 설정합니다. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 결제 참조를 최대 35자까지 가져오거나 설정합니다. |
|
|  | [getRemittance()](#getRemittance--) | 송금 정보를 최대 140자까지 가져오거나 설정합니다. |
|
|  | [setRemittance(String value)](#setRemittance-java.lang.String-) | 송금 정보를 최대 140자까지 가져오거나 설정합니다. |
|
|  | [getInformation()](#getInformation--) | 힌트 정보를 가져오거나 설정합니다. |
|
|  | [setInformation(String value)](#setInformation-java.lang.String-) | 힌트 정보를 가져오거나 설정합니다. |
|
|  | [getVersion()](#getVersion--) | EPC / SEPA QR-Code 버전 구현. |
|
|  | [setVersion(String value)](#setVersion-java.lang.String-) | EPC / SEPA QR-Code 버전 구현. |
|
|  | [getCharset()](#getCharset--) | EPC / SEPA QR-Code 문자 집합 구현. |
|
|  | [setCharset(String value)](#setCharset-java.lang.String-) | EPC / SEPA QR-Code 문자 집합 구현. |
|
|  | [getIdentification()](#getIdentification--) | EPC / SEPA QR-Code 식별. |
|
|  | [setIdentification(String value)](#setIdentification-java.lang.String-) | EPC / SEPA QR-Code 식별. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | EPC 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
### EPC() {#EPC--}
```
public EPC()
```


새 EPC 객체를 인스턴스화합니다.


### getName() {#getName--}
```
public final String getName()
```


수취인 이름을 가져오거나 설정합니다. 최대 길이는 70자입니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


수취인 이름을 가져오거나 설정합니다. 최대 길이는 70자입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getBIC() {#getBIC--}
```
public final String getBIC()
```


수취인 BIC를 최대 11자 길이로 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setBIC(String value) {#setBIC-java.lang.String-}
```
public final void setBIC(String value)
```


수취인 BIC를 최대 11자 길이로 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getIBAN() {#getIBAN--}
```
public final String getIBAN()
```


수취인 계좌(IBAN)를 가져오거나 설정합니다. IBAN은 최대 34개의 영숫자 문자로 구성됩니다.


**Returns:**
java.lang.String
### setIBAN(String value) {#setIBAN-java.lang.String-}
```
public final void setIBAN(String value)
```


수취인 계좌(IBAN)를 가져오거나 설정합니다. IBAN은 최대 34개의 영숫자 문자로 구성됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAmount() {#getAmount--}
```
public final double getAmount()
```


금액을 가져오거나 설정합니다.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


금액을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getCode() {#getCode--}
```
public final String getCode()
```


비즈니스 코드를 최대 4자까지 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setCode(String value) {#setCode-java.lang.String-}
```
public final void setCode(String value)
```


비즈니스 코드를 최대 4자까지 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getReference() {#getReference--}
```
public final String getReference()
```


결제 참조(최대 35자)를 가져오거나 설정합니다. 이 필드와 송금 정보 필드는 서로 배타적입니다.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


결제 참조(최대 35자)를 가져오거나 설정합니다. 이 필드와 송금 정보 필드는 서로 배타적입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getRemittance() {#getRemittance--}
```
public final String getRemittance()
```


송금 정보(최대 140자)를 가져오거나 설정합니다. 이 필드와 결제 참조 필드는 서로 배타적입니다.


**Returns:**
java.lang.String
### setRemittance(String value) {#setRemittance-java.lang.String-}
```
public final void setRemittance(String value)
```


송금 정보(최대 140자)를 가져오거나 설정합니다. 이 필드와 결제 참조 필드는 서로 배타적입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getInformation() {#getInformation--}
```
public final String getInformation()
```


힌트 정보를 가져오거나 설정합니다. 최대 70자.


**Returns:**
java.lang.String
### setInformation(String value) {#setInformation-java.lang.String-}
```
public final void setInformation(String value)
```


힌트 정보를 가져오거나 설정합니다. 최대 70자.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getVersion() {#getVersion--}
```
public final String getVersion()
```


EPC / SEPA QR-Code 버전 구현. 기본값은 002로 설정됩니다.


**Returns:**
java.lang.String
### setVersion(String value) {#setVersion-java.lang.String-}
```
public final void setVersion(String value)
```


EPC / SEPA QR-Code 버전 구현. 기본값은 002로 설정됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCharset() {#getCharset--}
```
public final String getCharset()
```


EPC / SEPA QR-Code 문자 집합 구현. 기본값은 1로 설정됩니다.


**Returns:**
java.lang.String
### setCharset(String value) {#setCharset-java.lang.String-}
```
public final void setCharset(String value)
```


EPC / SEPA QR-Code 문자 집합 구현. 기본값은 1로 설정됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getIdentification() {#getIdentification--}
```
public final String getIdentification()
```


EPC / SEPA QR-Code 식별. 기본값은 SCT로 설정됩니다.


**Returns:**
java.lang.String
### setIdentification(String value) {#setIdentification-java.lang.String-}
```
public final void setIdentification(String value)
```


EPC / SEPA QR-Code 식별. 기본값은 SCT로 설정됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


EPC 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 소스 | java.lang.Object | 비교할 EPC 객체. |
|

**Returns:**
boolean - 전달된 주소 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - Email 해시 코드

