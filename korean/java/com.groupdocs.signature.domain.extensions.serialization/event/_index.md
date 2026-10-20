---
title: "Event"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "표준 QR 코드 이벤트 세부 정보를 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/event/
---
**Inheritance:**
java.lang.Object
```
public final class Event
```

표준 QR 코드 이벤트 세부 정보를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Event()](#Event--) | 기본값으로 Event 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 이벤트 제목을 가져오거나 설정합니다. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 이벤트 제목을 가져오거나 설정합니다. |
|
|  | [getDescription()](#getDescription--) | 설명을 가져오거나 설정합니다. |
|
|  | [setDescription(String value)](#setDescription-java.lang.String-) | 설명을 가져오거나 설정합니다. |
|
|  | [getLocation()](#getLocation--) | 이벤트 위치를 가져오거나 설정합니다. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 이벤트 위치를 가져오거나 설정합니다. |
|
|  | [getStartDate()](#getStartDate--) | 이벤트 시작 날짜와 시간을 가져오거나 설정합니다. |
|
|  | [setStartDate(Date value)](#setStartDate-java.util.Date-) | 이벤트 시작 날짜와 시간을 가져오거나 설정합니다. |
|
|  | [getEndDate()](#getEndDate--) | 이벤트 종료 날짜와 시간을 가져오거나 설정합니다. |
|
|  | [setEndDate(Date value)](#setEndDate-java.util.Date-) | 이벤트 종료 날짜와 시간을 가져오거나 설정합니다. |
|
|  | [equals(Object source)](#equals-java.lang.Object-) | Event 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
### Event() {#Event--}
```
public Event()
```


기본값으로 Event 인스턴스를 생성합니다.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


이벤트 제목을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


이벤트 제목을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


설명을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```


설명을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


이벤트 위치를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


이벤트 위치를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getStartDate() {#getStartDate--}
```
public final Date getStartDate()
```


이벤트 시작 날짜와 시간을 가져오거나 설정합니다.


**Returns:**
java.util.Date
### setStartDate(Date value) {#setStartDate-java.util.Date-}
```
public final void setStartDate(Date value)
```


이벤트 시작 날짜와 시간을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getEndDate() {#getEndDate--}
```
public final Date getEndDate()
```


이벤트 종료 날짜와 시간을 가져오거나 설정합니다.


**Returns:**
java.util.Date
### setEndDate(Date value) {#setEndDate-java.util.Date-}
```
public final void setEndDate(Date value)
```


이벤트 종료 날짜와 시간을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### equals(Object source) {#equals-java.lang.Object-}
```
public boolean equals(Object source)
```


Event 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 소스 | java.lang.Object | 비교할 Event 객체. |
|

**Returns:**
boolean - 전달된 Event 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - Event 해시 코드

