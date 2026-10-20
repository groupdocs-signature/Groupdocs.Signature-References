---
title: "SMS"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "SMS 단문 메시지 서비스 세부 정보를 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/sms/
---
**Inheritance:**
java.lang.Object
```
public class SMS
```

SMS 단문 메시지 서비스 세부 정보를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SMS()](#SMS--) | 기본값으로 VCard 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getNumber()](#getNumber--) | SMS 수신자 전화번호를 가져오거나 설정합니다. |
|
|  | [setNumber(String value)](#setNumber-java.lang.String-) | SMS 수신자 전화번호를 가져오거나 설정합니다. |
|
|  | [getMessage()](#getMessage--) | SMS 메시지 내용을 가져오거나 설정합니다. |
|
|  | [setMessage(String value)](#setMessage-java.lang.String-) | SMS 메시지 내용을 가져오거나 설정합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | SMS 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
### SMS() {#SMS--}
```
public SMS()
```


기본값으로 VCard 인스턴스를 생성합니다.


### getNumber() {#getNumber--}
```
public final String getNumber()
```


SMS 수신자 전화번호를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setNumber(String value) {#setNumber-java.lang.String-}
```
public final void setNumber(String value)
```


SMS 수신자 전화번호를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMessage() {#getMessage--}
```
public final String getMessage()
```


SMS 메시지 내용을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setMessage(String value) {#setMessage-java.lang.String-}
```
public final void setMessage(String value)
```


SMS 메시지 내용을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


SMS 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 객체 | java.lang.Object | 비교할 SMS 객체. |
|

**Returns:**
boolean - 전달된 SMS 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - VCard 해시 코드

