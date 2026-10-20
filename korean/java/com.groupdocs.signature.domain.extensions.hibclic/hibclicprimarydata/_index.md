---
title: "HIBCLICPrimaryData"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "HIBC 의료 산업 바코드 위원회 LIC 라이선스 식별 코드 기본 데이터를 저장하기 위한 클래스."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.interfaces.IComplexData](../../com.groupdocs.signature.domain.extensions.interfaces/icomplexdata)
```
public class HIBCLICPrimaryData implements IComplexData
```

HIBC(Healthcare Industry Bar Code Council) LIC(Licensed Identification Code) 기본 데이터를 저장하기 위한 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [HIBCLICPrimaryData()](#HIBCLICPrimaryData--) | 기본 ctor() |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLabelerIdentificationCode()](#getLabelerIdentificationCode--) | 라벨러 식별 코드의 날짜를 식별합니다. |
|
|  | [setLabelerIdentificationCode(String value)](#setLabelerIdentificationCode-java.lang.String-) | 라벨러 식별 코드의 날짜를 식별합니다. |
|
|  | [getProductOrCatalogNumber()](#getProductOrCatalogNumber--) | 제품 또는 카탈로그 번호를 식별합니다. |
|
|  | [setProductOrCatalogNumber(String value)](#setProductOrCatalogNumber-java.lang.String-) | 제품 또는 카탈로그 번호를 식별합니다. |
|
|  | [getUnitOfMeasureID()](#getUnitOfMeasureID--) | 측정 단위 ID를 식별합니다. |
|
|  | [setUnitOfMeasureID(int value)](#setUnitOfMeasureID-int-) | 측정 단위 ID를 식별합니다. |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICPrimaryData() {#HIBCLICPrimaryData--}
```
public HIBCLICPrimaryData()
```


기본 ctor()


### getLabelerIdentificationCode() {#getLabelerIdentificationCode--}
```
public final String getLabelerIdentificationCode()
```


라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는
항상 알파벳으로 시작하는 4자리 영숫자 문자열이어야 합니다.


**Returns:**
java.lang.String
### setLabelerIdentificationCode(String value) {#setLabelerIdentificationCode-java.lang.String-}
```
public final void setLabelerIdentificationCode(String value)
```


라벨러 식별 코드의 날짜를 식별합니다. 라벨러 식별 코드는
항상 알파벳으로 시작하는 4자리 영숫자 문자열이어야 합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getProductOrCatalogNumber() {#getProductOrCatalogNumber--}
```
public final String getProductOrCatalogNumber()
```


제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 영숫자여야 합니다
길이가 최대 18자까지인 문자열.


**Returns:**
java.lang.String
### setProductOrCatalogNumber(String value) {#setProductOrCatalogNumber-java.lang.String-}
```
public final void setProductOrCatalogNumber(String value)
```


제품 또는 카탈로그 번호를 식별합니다. 제품 또는 카탈로그 번호는 영숫자여야 합니다
길이가 최대 18자까지인 문자열.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getUnitOfMeasureID() {#getUnitOfMeasureID--}
```
public final int getUnitOfMeasureID()
```


측정 단위 ID를 식별합니다. 측정 단위 ID는 0에서 9 사이의 정수값이어야 합니다.


**Returns:**
int
### setUnitOfMeasureID(int value) {#setUnitOfMeasureID-int-}
```
public final void setUnitOfMeasureID(int value)
```


측정 단위 ID를 식별합니다. 측정 단위 ID는 0에서 9 사이의 정수값이어야 합니다.


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
### getCodetext() {#getCodetext--}
```
public final IComplexCodetext getCodetext()
```




**Returns:**
com.aspose.barcode.complexbarcode.IComplexCodetext
