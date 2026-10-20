---
title: "Mailmark2D"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "Royal Mail 2D Mailmark에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2d/
---
**Inheritance:**
java.lang.Object
```
public class Mailmark2D
```

Royal Mail 2D Mailmark에 삽입된 텍스트를 인코딩하고 디코딩하기 위한 클래스.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Mailmark2D()](#Mailmark2D--) | 기본 기본 및 보조 데이터 값을 사용하여 Royal Mail Mailmark 결합 데이터를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getUPUCountryID()](#getUPUCountryID--) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
|
|  | [setUPUCountryID(String value)](#setUPUCountryID-java.lang.String-) | UPU 국가 ID를 식별합니다. 최대 길이: 4자. |
|
|  | [getInformationTypeID()](#getInformationTypeID--) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
|
|  | [setInformationTypeID(String value)](#setInformationTypeID-java.lang.String-) | 각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다. |
|
|  | [getVersionID()](#getVersionID--) | 각 Information Type ID와 관련된 바코드 버전을 식별합니다. |
|
|  | [getClass_()](#getClass---) | 항목의 클래스를 식별합니다. |
|
|  | [setClass(String value)](#setClass-java.lang.String-) | 항목의 클래스를 식별합니다. |
|
|  | [getSupplyChainID()](#getSupplyChainID--) | 메일링에 관여하는 고유한 고객 그룹을 식별합니다. |
|
|  | [setSupplyChainID(int value)](#setSupplyChainID-int-) | 메일링에 관여하는 고유한 고객 그룹을 식별합니다. |
|
|  | [getItemID()](#getItemID--) | Supply Chain ID 내의 고유 항목을 식별합니다. |
|
|  | [setItemID(int value)](#setItemID-int-) | Supply Chain ID 내의 고유 항목을 식별합니다. |
|
|  | [getDestinationPostCodeAndDPS()](#getDestinationPostCodeAndDPS--) | DPS가 포함된 배송 주소의 우편번호를 포함합니다. |
내륙인 경우, 우편번호/DP는 다음과 같은 문자 수를 포함합니다.
|
|  | [setDestinationPostCodeAndDPS(String value)](#setDestinationPostCodeAndDPS-java.lang.String-) | DPS가 포함된 배송 주소의 우편번호를 포함합니다. |
내륙인 경우, 우편번호/DP는 다음과 같은 문자 수를 포함합니다.
|
|  | [getRTSFlag()](#getRTSFlag--) | 반송 서비스 수준을 나타내는 플래그입니다. |
|
|  | [setRTSFlag(String value)](#setRTSFlag-java.lang.String-) | 반송 서비스 수준을 나타내는 플래그입니다. |
|
|  | [getReturnToSenderPostCode()](#getReturnToSenderPostCode--) | DPS 없이 반송 우편 코드를 포함합니다. |
|
|  | [setReturnToSenderPostCode(String value)](#setReturnToSenderPostCode-java.lang.String-) | DPS 없이 반송 우편 코드를 포함합니다. |
|
|  | [getCustomerContent()](#getCustomerContent--) | 고객이 사용할 수 있는 선택적 공간입니다. |
|
|  | [setCustomerContent(String value)](#setCustomerContent-java.lang.String-) | 고객이 사용할 수 있는 선택적 공간입니다. |
|
|  | [getCustomerContentEncodeMode()](#getCustomerContentEncodeMode--) | DataMatrix 바코드의 인코드 모드. |
|
|  | [setCustomerContentEncodeMode(int value)](#setCustomerContentEncodeMode-int-) | DataMatrix 바코드의 인코드 모드. |
|
|  | [getDataMatrixType()](#getDataMatrixType--) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
|
|  | [setDataMatrixType(int value)](#setDataMatrixType-int-) | 2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다. |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
### Mailmark2D() {#Mailmark2D--}
```
public Mailmark2D()
```


기본 기본 및 보조 데이터 값을 사용하여 Royal Mail Mailmark 결합 데이터를 생성합니다.


### getUPUCountryID() {#getUPUCountryID--}
```
public final String getUPUCountryID()
```


UPU 국가 ID를 식별합니다. 최대 길이: 4자.


**Returns:**
java.lang.String
### setUPUCountryID(String value) {#setUPUCountryID-java.lang.String-}
```
public final void setUPUCountryID(String value)
```


UPU 국가 ID를 식별합니다. 최대 길이: 4자.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getInformationTypeID() {#getInformationTypeID--}
```
public final String getInformationTypeID()
```


각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다.

<br />

*** ** * ** ***

유효값: "0" - 국내 정렬 및 비정렬 "A" - 온라인 우편 "B" - 프랭킹 "C" - 통합

<br />



**Returns:**
java.lang.String
### setInformationTypeID(String value) {#setInformationTypeID-java.lang.String-}
```
public final void setInformationTypeID(String value)
```


각 제품 유형에 대한 Royal Mail Mailmark 바코드 페이로드를 식별합니다.

<br />

*** ** * ** ***

유효값: "0" - 국내 정렬 및 비정렬 "A" - 온라인 우편 "B" - 프랭킹 "C" - 통합

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getVersionID() {#getVersionID--}
```
public final String getVersionID()
```


각 Information Type ID와 관련된 바코드 버전을 식별합니다.

<br />

*** ** * ** ***

유효값: "1" - 현재 사용되는 유일한 값(기본값) "0" 및 "2"~"9"와 "A"~"Z"는 향후 사용을 위해 예약된 여분 값입니다.

<br />



**Returns:**
java.lang.String
### getClass_() {#getClass---}
```
public final String getClass_()
```


항목의 클래스를 식별합니다.

<br />

*** ** * ** ***

유효값: "1" - 1C (소매) "2" - 2C(소매) "3" - Economy(소매) "5" - Deferred(소매) "8" - Premium(네트워크 액세스) "9" - Standard(네트워크 액세스)

<br />



**Returns:**
java.lang.String
### setClass(String value) {#setClass-java.lang.String-}
```
public final void setClass(String value)
```


항목의 클래스를 식별합니다.

<br />

*** ** * ** ***

유효값: "1" - 1C (소매) "2" - 2C(소매) "3" - Economy(소매) "5" - Deferred(소매) "8" - Premium(네트워크 액세스) "9" - Standard(네트워크 액세스)

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSupplyChainID() {#getSupplyChainID--}
```
public final int getSupplyChainID()
```


메일링에 관여하는 고유한 고객 그룹을 식별합니다.
최대값: 9999999.


**Returns:**
int
### setSupplyChainID(int value) {#setSupplyChainID-int-}
```
public final void setSupplyChainID(int value)
```


메일링에 관여하는 고유한 고객 그룹을 식별합니다.
최대값: 9999999.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getItemID() {#getItemID--}
```
public final int getItemID()
```


Supply Chain ID 내의 고유 항목을 식별합니다.
모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다.
최대값: 99999999.


**Returns:**
int
### setItemID(int value) {#setItemID-int-}
```
public final void setItemID(int value)
```


Supply Chain ID 내의 고유 항목을 식별합니다.
모든 Mailmark 바코드는 최소 90일 동안 고유하게 식별될 수 있도록 ID를 포함해야 합니다.
최대값: 99999999.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDestinationPostCodeAndDPS() {#getDestinationPostCodeAndDPS--}
```
public final String getDestinationPostCodeAndDPS()
```


DPS가 포함된 배송 주소의 우편번호를 포함합니다.
내륙인 경우, 우편번호/DP는 다음과 같은 문자 수를 포함합니다.
지역 (1~2자)
구역(1~2자)
섹터(1자)
단위(2자)
DPS (2자).
우편번호와 DPS는 유효한 PAF® 형식을 따라야 합니다. 최대 길이는 9입니다.


**Returns:**
java.lang.String
### setDestinationPostCodeAndDPS(String value) {#setDestinationPostCodeAndDPS-java.lang.String-}
```
public final void setDestinationPostCodeAndDPS(String value)
```


DPS가 포함된 배송 주소의 우편번호를 포함합니다.
내륙인 경우, 우편번호/DP는 다음과 같은 문자 수를 포함합니다.
지역 (1~2자)
구역(1~2자)
섹터(1자)
단위(2자)
DPS (2자).
우편번호와 DPS는 유효한 PAF® 형식을 따라야 합니다. 최대 길이는 9입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getRTSFlag() {#getRTSFlag--}
```
public final String getRTSFlag()
```


반송 서비스 수준을 나타내는 플래그입니다. 최대 길이는 1입니다.


**Returns:**
java.lang.String
### setRTSFlag(String value) {#setRTSFlag-java.lang.String-}
```
public final void setRTSFlag(String value)
```


반송 서비스 수준을 나타내는 플래그입니다. 최대 길이는 1입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getReturnToSenderPostCode() {#getReturnToSenderPostCode--}
```
public final String getReturnToSenderPostCode()
```


DPS 없이 반송 우편 코드를 포함합니다.
PC(DPS 없이) 는 PAF® 형식을 따라야 합니다.


**Returns:**
java.lang.String
### setReturnToSenderPostCode(String value) {#setReturnToSenderPostCode-java.lang.String-}
```
public final void setReturnToSenderPostCode(String value)
```


DPS 없이 반송 우편 코드를 포함합니다.
PC(DPS 없이) 는 PAF® 형식을 따라야 합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCustomerContent() {#getCustomerContent--}
```
public final String getCustomerContent()
```


고객이 사용할 수 있는 선택적 공간입니다.

<br />

*** ** * ** ***

유형별 최대 길이 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): 유형 7: 6자 유형 9: 45자 유형 29: 25자

<br />



**Returns:**
java.lang.String
### setCustomerContent(String value) {#setCustomerContent-java.lang.String-}
```
public final void setCustomerContent(String value)
```


고객이 사용할 수 있는 선택적 공간입니다.

<br />

*** ** * ** ***

유형별 최대 길이 [Mailmark2DType](../../com.groupdocs.signature.domain.extensions.mailmark2d/mailmark2dtype): 유형 7: 6자 유형 9: 45자 유형 29: 25자

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCustomerContentEncodeMode() {#getCustomerContentEncodeMode--}
```
public final int getCustomerContentEncodeMode()
```


DataMatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Returns:**
int
### setCustomerContentEncodeMode(int value) {#setCustomerContentEncodeMode-int-}
```
public final void setCustomerContentEncodeMode(int value)
```


DataMatrix 바코드의 인코드 모드입니다. 기본값: DataMatrixEncodeMode.C40. [DataMatrixEncodeMode](../../com.groupdocs.signature.domain.extensions.serialization/datamatrixencodemode)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDataMatrixType() {#getDataMatrixType--}
```
public final int getDataMatrixType()
```


2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다.


**Returns:**
int
### setDataMatrixType(int value) {#setDataMatrixType-int-}
```
public final void setDataMatrixType(int value)
```


2D Mailmark 유형은 Data Matrix 바코드의 크기를 정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 객체의 복사본을 가져옵니다.


**Returns:**
java.lang.Object
