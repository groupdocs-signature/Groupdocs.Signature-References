---
title: "HIBCLICCombinedData"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "주요 및 보조 데이터 엔터티와 함께 HIBC Healthcare Industry Bar Code Council LIC Licensed Identification Code 결합 데이터를 저장하기 위한 클래스."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.extensions.hibclic/hibcliccombineddata/
---
**Inheritance:**
java.lang.Object
```
public class HIBCLICCombinedData
```

주요 및 보조 데이터 엔터티와 결합된 HIBC(Healthcare Industry Bar Code Council) LIC(Licensed Identification Code) 데이터를 저장하기 위한 클래스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [HIBCLICCombinedData()](#HIBCLICCombinedData--) | 기본 주요 및 보조 데이터 값을 사용하여 HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) 결합 데이터를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPrimaryData()](#getPrimaryData--) | HIBC LIC 기본 데이터 구조 |
|
|  | [setPrimaryData(HIBCLICPrimaryData value)](#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-) | HIBC LIC 기본 데이터 구조 |
|
|  | [getSecondaryAdditionalData()](#getSecondaryAdditionalData--) | HIBC LIC 보조 데이터 구조 |
|
|  | [setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)](#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-) | HIBC LIC 보조 데이터 구조 |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
| [getCodetext()](#getCodetext--) |  |
### HIBCLICCombinedData() {#HIBCLICCombinedData--}
```
public HIBCLICCombinedData()
```


기본 주요 및 보조 데이터 값을 사용하여 HIBC (Healthcare Industry Bar Code Council) LIC (Licensed Identification Code) 결합 데이터를 생성합니다.


### getPrimaryData() {#getPrimaryData--}
```
public final HIBCLICPrimaryData getPrimaryData()
```


HIBC LIC 기본 데이터 구조


**Returns:**
[HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata)
### setPrimaryData(HIBCLICPrimaryData value) {#setPrimaryData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICPrimaryData-}
```
public final void setPrimaryData(HIBCLICPrimaryData value)
```


HIBC LIC 기본 데이터 구조


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [HIBCLICPrimaryData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicprimarydata) |  |

### getSecondaryAdditionalData() {#getSecondaryAdditionalData--}
```
public final HIBCLICSecondaryAdditionalData getSecondaryAdditionalData()
```


HIBC LIC 보조 데이터 구조


**Returns:**
[HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata)
### setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value) {#setSecondaryAdditionalData-com.groupdocs.signature.domain.extensions.hibclic.HIBCLICSecondaryAdditionalData-}
```
public final void setSecondaryAdditionalData(HIBCLICSecondaryAdditionalData value)
```


HIBC LIC 보조 데이터 구조


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [HIBCLICSecondaryAdditionalData](../../com.groupdocs.signature.domain.extensions.hibclic/hibclicsecondaryadditionaldata) |  |

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
