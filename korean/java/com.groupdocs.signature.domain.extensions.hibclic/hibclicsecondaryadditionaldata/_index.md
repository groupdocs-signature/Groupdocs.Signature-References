---
title: "HIBCLICSecondaryAdditionalData"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "HIBC 의료 산업 바코드 위원회 LIC 라이선스 식별 코드의 보조 및 추가 데이터를 저장하기 위한 클래스."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICSecondaryAdditionalData implements IComplexData
```

HIBC(Healthcare Industry Bar Code Council) LIC(Licensed Identification Code)의 보조 및 추가 데이터를 저장하기 위한 클래스.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [HIBCLICSecondaryAdditionalData()](#HIBCLICSecondaryAdditionalData--) | 기본 ctor() |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getExpiryDateFormat()](#getExpiryDateFormat--) | 만료 날짜 형식을 식별합니다. |
|
|  | [setExpiryDateFormat(int value)](#setExpiryDateFormat-int-) | 만료 날짜 형식을 식별합니다. |
|
|  | [getExpiryDate()](#getExpiryDate--) | 만료 날짜를 식별합니다. |
|
|  | [setExpiryDate(Date value)](#setExpiryDate-java.util.Date-) | 만료 날짜를 식별합니다. |
|
|  | [getLotNumber()](#getLotNumber--) | LOT 또는 배치 번호를 식별합니다. |
|
|  | [setLotNumber(String value)](#setLotNumber-java.lang.String-) | LOT 또는 배치 번호를 식별합니다. |
|
|  | [getSerialNumber()](#getSerialNumber--) | 시리얼 번호를 식별합니다. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 시리얼 번호를 식별합니다. |
|
|  | [getDateOfManufacture()](#getDateOfManufacture--) | 제조 날짜를 식별합니다. |
|
|  | [setDateOfManufacture(Date value)](#setDateOfManufacture-java.util.Date-) | 제조 날짜를 식별합니다. |
|
|  | [getQuantity()](#getQuantity--) | 수량을 식별합니다. 수량은 0에서 500 사이의 정수값이어야 합니다. |
|
|  | [setQuantity(int value)](#setQuantity-int-) | 수량을 식별합니다. 수량은 0에서 500 사이의 정수값이어야 합니다. |
|
|  | [getLinkCharacter()](#getLinkCharacter--) | 출력 문자열에서 링크 문자를 식별합니다. |
|
|  | [setLinkCharacter(char value)](#setLinkCharacter-char-) | 출력 문자열에서 링크 문자를 식별합니다. |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
### HIBCLICSecondaryAdditionalData() {#HIBCLICSecondaryAdditionalData--}
```
public HIBCLICSecondaryAdditionalData()
```


기본 ctor()


### getExpiryDateFormat() {#getExpiryDateFormat--}
```
public final int getExpiryDateFormat()
```


만료 날짜 형식을 식별합니다.


**Returns:**
int
### setExpiryDateFormat(int value) {#setExpiryDateFormat-int-}
```
public final void setExpiryDateFormat(int value)
```


만료 날짜 형식을 식별합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getExpiryDate() {#getExpiryDate--}
```
public final Date getExpiryDate()
```


만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.


**Returns:**
java.util.Date
### setExpiryDate(Date value) {#setExpiryDate-java.util.Date-}
```
public final void setExpiryDate(Date value)
```


만료 날짜를 식별합니다. ExpiryDateFormat이 None으로 설정되지 않은 경우 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getLotNumber() {#getLotNumber--}
```
public final String getLotNumber()
```


LOT 또는 배치 번호를 식별합니다.
Lot/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.


**Returns:**
java.lang.String
### setLotNumber(String value) {#setLotNumber-java.lang.String-}
```
public final void setLotNumber(String value)
```


LOT 또는 배치 번호를 식별합니다.
Lot/배치 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


시리얼 번호를 식별합니다.
시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


시리얼 번호를 식별합니다.
시리얼 번호는 최대 18자 길이의 영숫자 문자열이어야 합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getDateOfManufacture() {#getDateOfManufacture--}
```
public final Date getDateOfManufacture()
```


제조 날짜를 식별합니다.
제조 날짜는 이 필드를 사용하지 않으려면 DateTime.MinValue로 설정할 수 있습니다.
기본값: DateTime.MinValue


**Returns:**
java.util.Date
### setDateOfManufacture(Date value) {#setDateOfManufacture-java.util.Date-}
```
public final void setDateOfManufacture(Date value)
```


제조 날짜를 식별합니다.
제조 날짜는 이 필드를 사용하지 않으려면 DateTime.MinValue로 설정할 수 있습니다.
기본값: DateTime.MinValue


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getQuantity() {#getQuantity--}
```
public final int getQuantity()
```


수량을 식별합니다. 수량은 0에서 500 사이의 정수값이어야 합니다.
수량은 이 필드를 사용하지 않으려면 -1로 설정할 수 있습니다. 기본값: -1


**Returns:**
int
### setQuantity(int value) {#setQuantity-int-}
```
public final void setQuantity(int value)
```


수량을 식별합니다. 수량은 0에서 500 사이의 정수값이어야 합니다.
수량은 이 필드를 사용하지 않으려면 -1로 설정할 수 있습니다. 기본값: -1


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLinkCharacter() {#getLinkCharacter--}
```
public final char getLinkCharacter()
```


출력 문자열에서 링크 문자를 식별합니다.


**Returns:**
문자
### setLinkCharacter(char value) {#setLinkCharacter-char-}
```
public final void setLinkCharacter(char value)
```


출력 문자열에서 링크 문자를 식별합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | 문자 |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 객체의 복사본을 가져옵니다.


**Returns:**
java.lang.Object
