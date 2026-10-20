---
title: "SwissAddress"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "채권자 또는 채무자의 주소를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.extensions.swissqr/swissaddress/
---
**Inheritance:**
java.lang.Object
```
public class SwissAddress
```

채권자 또는 채무자의 주소를 나타냅니다.
거리, 건물 번호, 우편 번호 및 도시(구조화된 주소 유형)를 설정할 수 있습니다.
또는 주소 라인 1 및 2(결합된 주소 요소 유형)입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [SwissAddress()](#SwissAddress--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 이름을 가져오거나 설정합니다. 자연인의 이름과 성 또는 |
법인(법인)의 회사 이름입니다.
|
|  | [setName(String value)](#setName-java.lang.String-) | 이름을 가져오거나 설정합니다. 자연인의 이름과 성 또는 |
법인(법인)의 회사 이름입니다.
|
|  | [getAddressLine1()](#getAddressLine1--) | 주소 라인 1을 가져오거나 설정합니다. |
|
|  | [setAddressLine1(String value)](#setAddressLine1-java.lang.String-) | 주소 라인 1을 가져오거나 설정합니다. |
|
|  | [getAddressLine2()](#getAddressLine2--) | 주소 라인 2를 가져오거나 설정합니다. |
|
|  | [setAddressLine2(String value)](#setAddressLine2-java.lang.String-) | 주소 라인 2를 가져오거나 설정합니다. |
|
|  | [getStreet()](#getStreet--) | 거리를 가져오거나 설정합니다. |
|
|  | [setStreet(String value)](#setStreet-java.lang.String-) | 거리를 가져오거나 설정합니다. |
|
|  | [getHouseNo()](#getHouseNo--) | 건물 번호를 가져오거나 설정합니다. |
|
|  | [setHouseNo(String value)](#setHouseNo-java.lang.String-) | 건물 번호를 가져오거나 설정합니다. |
|
|  | [getPostalCode()](#getPostalCode--) | 우편 번호를 가져오거나 설정합니다. |
|
|  | [setPostalCode(String value)](#setPostalCode-java.lang.String-) | 우편 번호를 가져오거나 설정합니다. |
|
|  | [getTown()](#getTown--) | 도시 또는 마을을 가져오거나 설정합니다. |
|
|  | [setTown(String value)](#setTown-java.lang.String-) | 도시 또는 마을을 가져오거나 설정합니다. |
|
|  | [getCountryCode()](#getCountryCode--) | 두 글자 ISO 국가 코드를 가져오거나 설정합니다. |
|
|  | [setCountryCode(String value)](#setCountryCode-java.lang.String-) | 두 글자 ISO 국가 코드를 가져오거나 설정합니다. |
|
### SwissAddress() {#SwissAddress--}
```
public SwissAddress()
```


### getName() {#getName--}
```
public final String getName()
```


이름을 가져오거나 설정합니다. 자연인의 이름과 성 또는
법인(법인)의 회사 이름입니다.
값: 이름.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


이름을 가져오거나 설정합니다. 자연인의 이름과 성 또는
법인(법인)의 회사 이름입니다.
값: 이름.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAddressLine1() {#getAddressLine1--}
```
public final String getAddressLine1()
```


주소 라인 1을 가져오거나 설정합니다.
주소 라인 1에는 거리 이름, 집 번호 또는 사서함이 포함됩니다.
이 필드는 결합된 요소 주소에만 사용되며 선택 사항입니다.
값: 주소 라인 1.


**Returns:**
java.lang.String
### setAddressLine1(String value) {#setAddressLine1-java.lang.String-}
```
public final void setAddressLine1(String value)
```


주소 라인 1을 가져오거나 설정합니다.
주소 라인 1에는 거리 이름, 집 번호 또는 사서함이 포함됩니다.
이 필드는 결합된 요소 주소에만 사용되며 선택 사항입니다.
값: 주소 라인 1.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAddressLine2() {#getAddressLine2--}
```
public final String getAddressLine2()
```


주소 라인 2를 가져오거나 설정합니다.
주소 라인 2에는 우편 번호와 도시가 포함됩니다.
이 필드는 결합된 요소 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 주소 라인 2.


**Returns:**
java.lang.String
### setAddressLine2(String value) {#setAddressLine2-java.lang.String-}
```
public final void setAddressLine2(String value)
```


주소 라인 2를 가져오거나 설정합니다.
주소 라인 2에는 우편 번호와 도시가 포함됩니다.
이 필드는 결합된 요소 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 주소 라인 2.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getStreet() {#getStreet--}
```
public final String getStreet()
```


거리를 가져오거나 설정합니다.
거리에는 집 번호 없이 지정해야 합니다.
이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.
값: 거리.


**Returns:**
java.lang.String
### setStreet(String value) {#setStreet-java.lang.String-}
```
public final void setStreet(String value)
```


거리를 가져오거나 설정합니다.
거리에는 집 번호 없이 지정해야 합니다.
이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.
값: 거리.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getHouseNo() {#getHouseNo--}
```
public final String getHouseNo()
```


건물 번호를 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.
값: 집 번호.


**Returns:**
java.lang.String
### setHouseNo(String value) {#setHouseNo-java.lang.String-}
```
public final void setHouseNo(String value)
```


건물 번호를 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용되며 선택 사항입니다.
값: 집 번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getPostalCode() {#getPostalCode--}
```
public final String getPostalCode()
```


우편 번호를 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 우편 번호.


**Returns:**
java.lang.String
### setPostalCode(String value) {#setPostalCode-java.lang.String-}
```
public final void setPostalCode(String value)
```


우편 번호를 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 우편 번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTown() {#getTown--}
```
public final String getTown()
```


도시 또는 마을을 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 도시 또는 마을.


**Returns:**
java.lang.String
### setTown(String value) {#setTown-java.lang.String-}
```
public final void setTown(String value)
```


도시 또는 마을을 가져오거나 설정합니다.
이 필드는 구조화된 주소에만 사용됩니다. 이 유형의 경우 필수입니다.
값: 도시 또는 마을.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCountryCode() {#getCountryCode--}
```
public final String getCountryCode()
```


두 글자 ISO 국가 코드를 가져오거나 설정합니다.
전체 주소에 null 또는 빈 값이 포함되지 않는 한 국가 코드는 필수입니다.
값: ISO 국가 코드.


**Returns:**
java.lang.String
### setCountryCode(String value) {#setCountryCode-java.lang.String-}
```
public final void setCountryCode(String value)
```


두 글자 ISO 국가 코드를 가져오거나 설정합니다.
전체 주소에 null 또는 빈 값이 포함되지 않는 한 국가 코드는 필수입니다.
값: ISO 국가 코드.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

