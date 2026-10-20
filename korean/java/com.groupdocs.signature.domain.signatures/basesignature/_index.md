---
title: "BaseSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명을 위한 기본 클래스를 설명합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.signatures/basesignature/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseSignature
```

서명을 위한 기본 클래스를 설명합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSignatureType()](#getSignatureType--) | 서명의 유형을 지정합니다. |
|
|  | [getPageNumber()](#getPageNumber--) | 서명이 발견된 페이지를 지정합니다. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 서명이 발견된 페이지를 지정합니다. |
|
|  | [getSignatureId()](#getSignatureId--) | 업데이트 또는 삭제 메서드를 통해 문서에서 서명을 수정하기 위한 고유 서명 식별자입니다. |
|
|  | [isSignature()](#isSignature--) | 이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다. |
|
|  | [setSignature(boolean value)](#setSignature-boolean-) | 이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다. |
|
|  | [getDeleted()](#getDeleted--) | 이 서명이 문서에서 삭제되었는지 여부를 표시하는 플래그를 가져오거나 설정합니다. |
|
|  | [getCreatedOn()](#getCreatedOn--) | 서명 생성 날짜를 가져오거나 설정합니다. |
|
|  | [setCreatedOn(Date value)](#setCreatedOn-java.util.Date-) | 서명 생성 날짜를 가져오거나 설정합니다. |
|
|  | [getModifiedOn()](#getModifiedOn--) | 서명 수정 날짜를 가져오거나 설정합니다. |
|
|  | [setModifiedOn(Date value)](#setModifiedOn-java.util.Date-) | 서명 수정 날짜를 가져오거나 설정합니다. |
|
|  | [getTop()](#getTop--) | 서명의 상단 위치를 지정합니다. |
|
|  | [setTop(int value)](#setTop-int-) | 서명의 상단 위치를 지정합니다. |
|
|  | [getLeft()](#getLeft--) | 서명의 왼쪽 위치를 지정합니다. |
|
|  | [setLeft(int value)](#setLeft-int-) | 서명의 왼쪽 위치를 지정합니다. |
|
|  | [getWidth()](#getWidth--) | 서명의 너비를 지정합니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 서명의 너비를 지정합니다. |
|
|  | [getHeight()](#getHeight--) | 서명의 높이를 지정합니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 서명의 높이를 지정합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
| [supportMetaInfoLayer()](#supportMetaInfoLayer--) |  |
|  | [toString()](#toString--) | <br /> |

|
### getSignatureType() {#getSignatureType--}
```
public final int getSignatureType()
```


서명의 유형을 지정합니다. 디지털 서명은 이 속성을 가집니다.


**Returns:**
int
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


서명이 발견된 페이지를 지정합니다.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


서명이 발견된 페이지를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getSignatureId() {#getSignatureId--}
```
public final String getSignatureId()
```


업데이트 또는 삭제 메서드를 통해 문서에서 서명을 수정하기 위한 고유 서명 식별자입니다.
이 속성은 Sign 또는 Search 메서드가 호출된 후 자동으로 설정됩니다.
이 속성이 이전에 저장된 경우, 서명을 조작하기 위해 수동으로 설정할 수 있습니다.


**Returns:**
java.lang.String
### isSignature() {#isSignature--}
```
public final boolean isSignature()
```


이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다.
이 속성은 Update 메서드와 함께 사용되어 요소를 서명(true) 또는 문서 요소(false)로 설정합니다.


**Returns:**
boolean
### setSignature(boolean value) {#setSignature-boolean-}
```
public final void setSignature(boolean value)
```


이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다.
이 속성은 Update 메서드와 함께 사용되어 요소를 서명(true) 또는 문서 요소(false)로 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDeleted() {#getDeleted--}
```
public final boolean getDeleted()
```


이 서명이 문서에서 삭제되었는지 여부를 표시하는 플래그를 가져오거나 설정합니다.
이 속성은 문서 기록 로그 레코드에서 삭제된 서명의 목록을 유지하기 위해서만 사용됩니다.


**Returns:**
boolean
### getCreatedOn() {#getCreatedOn--}
```
public final Date getCreatedOn()
```


서명 생성 날짜를 가져오거나 설정합니다.


**Returns:**
java.util.Date
### setCreatedOn(Date value) {#setCreatedOn-java.util.Date-}
```
public final void setCreatedOn(Date value)
```


서명 생성 날짜를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getModifiedOn() {#getModifiedOn--}
```
public final Date getModifiedOn()
```


서명 수정 날짜를 가져오거나 설정합니다.


**Returns:**
java.util.Date
### setModifiedOn(Date value) {#setModifiedOn-java.util.Date-}
```
public final void setModifiedOn(Date value)
```


서명 수정 날짜를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getTop() {#getTop--}
```
public final int getTop()
```


서명의 상단 위치를 지정합니다.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


서명의 상단 위치를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


서명의 왼쪽 위치를 지정합니다.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


서명의 왼쪽 위치를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


서명의 너비를 지정합니다.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


서명의 너비를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


서명의 높이를 지정합니다.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


서명의 높이를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 서명 | java.lang.Object | 비교할 서명 객체. |
|

**Returns:**
boolean - 전달된 서명 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int -
### supportMetaInfoLayer() {#supportMetaInfoLayer--}
```
public boolean supportMetaInfoLayer()
```




**Returns:**
boolean
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String -
