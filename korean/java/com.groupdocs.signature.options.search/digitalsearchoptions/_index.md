---
title: "DigitalSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "디지털 서명 검색을 위한 기본 옵션을 나타냅니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.search/digitalsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class DigitalSearchOptions extends SearchOptions
```

디지털 서명 검색을 위한 기본 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalSearchOptions()](#DigitalSearchOptions--) | DigitalSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getComments()](#getComments--) | 검색할 디지털 서명의 주석. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 검색할 디지털 서명의 주석. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 검색할 디지털 서명의 날짜 및 시간 범위. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 검색할 디지털 서명의 날짜 및 시간 범위. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | 검색할 디지털 서명의 날짜 및 시간 범위. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 검색할 디지털 서명의 날짜 및 시간 범위. |
|
|  | [getSubjectName()](#getSubjectName--) | 비어 있지 않은 값에 대해 검색할 인증서의 구별된 주체 이름을 지정합니다. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 비어 있지 않은 값에 대해 검색할 인증서의 구별된 주체 이름을 지정합니다. |
|
|  | [getIssuerName()](#getIssuerName--) | 비어 있지 않은 값에 대해 검색할 인증서 발급자의 구별된 이름을 지정합니다. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 비어 있지 않은 값에 대해 검색할 인증서 발급자의 구별된 이름을 지정합니다. |
|
### DigitalSearchOptions() {#DigitalSearchOptions--}
```
public DigitalSearchOptions()
```


DigitalSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### getComments() {#getComments--}
```
public final String getComments()
```


검색할 디지털 서명의 주석.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


검색할 디지털 서명의 주석.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public final Date getSignDateTimeFrom()
```


검색할 디지털 서명의 날짜 및 시간 범위. null 허용 값은 무시됩니다.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public final void setSignDateTimeFrom(Date value)
```


검색할 디지털 서명의 날짜 및 시간 범위. null 허용 값은 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public final Date getSignDateTimeTo()
```


검색할 디지털 서명의 날짜 및 시간 범위. null 허용 값은 무시됩니다.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public final void setSignDateTimeTo(Date value)
```


검색할 디지털 서명의 날짜 및 시간 범위. null 허용 값은 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


비어 있지 않은 값에 대해 검색할 인증서의 구별된 주체 이름을 지정합니다.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


비어 있지 않은 값에 대해 검색할 인증서의 구별된 주체 이름을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


비어 있지 않은 값에 대해 검색할 인증서 발급자의 구별된 이름을 지정합니다.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


비어 있지 않은 값에 대해 검색할 인증서 발급자의 구별된 이름을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

