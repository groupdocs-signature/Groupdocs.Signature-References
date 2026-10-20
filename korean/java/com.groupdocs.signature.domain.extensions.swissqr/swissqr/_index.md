---
title: "SwissQR"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "SwissQR 코드에 포함된 텍스트를 인코딩 및 디코딩하는 클래스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.extensions.swissqr/swissqr/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class SwissQR implements IComplexData
```

SwissQR 코드에 포함된 텍스트를 인코딩 및 디코딩하는 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SwissQR()](#SwissQR--) | SwissQR의 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAmount()](#getAmount--) | 결제 금액을 가져오거나 설정합니다. |
|
|  | [setAmount(double value)](#setAmount-double-) | 결제 금액을 가져오거나 설정합니다. |
|
|  | [getCurrency()](#getCurrency--) | 결제 통화를 가져오거나 설정합니다. |
|
|  | [setCurrency(String value)](#setCurrency-java.lang.String-) | 결제 통화를 가져오거나 설정합니다. |
|
|  | [getAccount()](#getAccount--) | 채권자의 계좌 번호를 가져오거나 설정합니다. |
|
|  | [setAccount(String value)](#setAccount-java.lang.String-) | 채권자의 계좌 번호를 가져오거나 설정합니다. |
|
|  | [getCreditor()](#getCreditor--) | 채권자 주소를 가져오거나 설정합니다. |
|
|  | [setCreditor(SwissAddress value)](#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 채권자 주소를 가져오거나 설정합니다. |
|
|  | [getReference()](#getReference--) | 채권자 결제 참조를 가져오거나 설정합니다. |
|
|  | [setReference(String value)](#setReference-java.lang.String-) | 채권자 결제 참조를 가져오거나 설정합니다. |
|
|  | [getDebtor()](#getDebtor--) | 채무자 주소를 가져오거나 설정합니다. |
|
|  | [setDebtor(SwissAddress value)](#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-) | 채무자 주소를 가져오거나 설정합니다. |
|
|  | [getUnstructuredMessage()](#getUnstructuredMessage--) | 추가 비구조화 메시지를 가져오거나 설정합니다. |
|
|  | [setUnstructuredMessage(String value)](#setUnstructuredMessage-java.lang.String-) | 추가 비구조화 메시지를 가져오거나 설정합니다. |
|
|  | [getBillInformation()](#getBillInformation--) | 추가 구조화된 청구서 정보를 가져오거나 설정합니다. |
|
|  | [setBillInformation(String value)](#setBillInformation-java.lang.String-) | 추가 구조화된 청구서 정보를 가져오거나 설정합니다. |
|
### SwissQR() {#SwissQR--}
```
public SwissQR()
```


SwissQR의 인스턴스를 생성합니다.


### getAmount() {#getAmount--}
```
public final double getAmount()
```


결제 금액을 가져오거나 설정합니다.
유효한 값은 0.01에서 999,999,999.99 사이입니다.
값: 결제 금액.


**Returns:**
double
### setAmount(double value) {#setAmount-double-}
```
public final void setAmount(double value)
```


결제 금액을 가져오거나 설정합니다.
유효한 값은 0.01에서 999,999,999.99 사이입니다.
값: 결제 금액.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getCurrency() {#getCurrency--}
```
public final String getCurrency()
```


결제 통화를 가져오거나 설정합니다.
유효한 값은 "CHF"와 "EUR"입니다.
값: 결제 통화.


**Returns:**
java.lang.String
### setCurrency(String value) {#setCurrency-java.lang.String-}
```
public final void setCurrency(String value)
```


결제 통화를 가져오거나 설정합니다.
유효한 값은 "CHF"와 "EUR"입니다.
값: 결제 통화.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAccount() {#getAccount--}
```
public final String getAccount()
```


채권자의 계좌 번호를 가져오거나 설정합니다.
계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다.
계좌 번호에 공백을 허용합니다.
값: 채권자 계좌 번호.


**Returns:**
java.lang.String
### setAccount(String value) {#setAccount-java.lang.String-}
```
public final void setAccount(String value)
```


채권자의 계좌 번호를 가져오거나 설정합니다.
계좌 번호는 스위스 또는 리히텐슈타인 은행의 유효한 IBAN이어야 합니다.
계좌 번호에 공백을 허용합니다.
값: 채권자 계좌 번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCreditor() {#getCreditor--}
```
public final SwissAddress getCreditor()
```


채권자 주소를 가져오거나 설정합니다.
값: 채권자 주소.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setCreditor(SwissAddress value) {#setCreditor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setCreditor(SwissAddress value)
```


채권자 주소를 가져오거나 설정합니다.
값: 채권자 주소.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getReference() {#getReference--}
```
public final String getReference()
```


채권자 결제 참조를 가져오거나 설정합니다.
SwissQR IBAN에 대해서는 참조가 필수이며, 즉 CHxx30000xxxxxx 범위의 IBAN에 해당합니다.
CHxx31999xxxxx까지.
지정된 경우, 참조는 유효한 SwissQR 참조(해당
ISR 참조 형식) 또는 ISO 11649("RFxxxx")에 따른 유효한 채권자 참조여야 합니다.
두 경우 모두 서식을 위해 공백을 포함할 수 있습니다.
값: 채권자 결제 참조.


**Returns:**
java.lang.String
### setReference(String value) {#setReference-java.lang.String-}
```
public final void setReference(String value)
```


채권자 결제 참조를 가져오거나 설정합니다.
SwissQR IBAN에 대해서는 참조가 필수이며, 즉 CHxx30000xxxxxx 범위의 IBAN에 해당합니다.
CHxx31999xxxxx까지.
지정된 경우, 참조는 유효한 SwissQR 참조(해당
ISR 참조 형식) 또는 ISO 11649("RFxxxx")에 따른 유효한 채권자 참조여야 합니다.
두 경우 모두 서식을 위해 공백을 포함할 수 있습니다.
값: 채권자 결제 참조.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getDebtor() {#getDebtor--}
```
public final SwissAddress getDebtor()
```


채무자 주소를 가져오거나 설정합니다.
채무자는 선택 사항입니다. 생략되는 경우, 이 필드를 null로 설정하거나
모든 값이 null이거나 비어 있는 주소를 설정하는 것도 허용됩니다.
값: 채무자 주소.


**Returns:**
[SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress)
### setDebtor(SwissAddress value) {#setDebtor-com.groupdocs.signature.domain.extensions.swissqr.SwissAddress-}
```
public final void setDebtor(SwissAddress value)
```


채무자 주소를 가져오거나 설정합니다.
채무자는 선택 사항입니다. 생략되는 경우, 이 필드를 null로 설정하거나
모든 값이 null이거나 비어 있는 주소를 설정하는 것도 허용됩니다.
값: 채무자 주소.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SwissAddress](../../com.groupdocs.signature.domain.extensions.swissqr/swissaddress) |  |

### getUnstructuredMessage() {#getUnstructuredMessage--}
```
public final String getUnstructuredMessage()
```


추가 비구조화 메시지를 가져오거나 설정합니다.
값: 비구조화 메시지.


**Returns:**
java.lang.String
### setUnstructuredMessage(String value) {#setUnstructuredMessage-java.lang.String-}
```
public final void setUnstructuredMessage(String value)
```


추가 비구조화 메시지를 가져오거나 설정합니다.
값: 비구조화 메시지.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getBillInformation() {#getBillInformation--}
```
public final String getBillInformation()
```


추가 구조화된 청구서 정보를 가져오거나 설정합니다.
값: 구조화된 청구 정보.


**Returns:**
java.lang.String
### setBillInformation(String value) {#setBillInformation-java.lang.String-}
```
public final void setBillInformation(String value)
```


추가 구조화된 청구서 정보를 가져오거나 설정합니다.
값: 구조화된 청구 정보.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

