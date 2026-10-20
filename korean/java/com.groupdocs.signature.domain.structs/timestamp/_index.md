---
title: "TimeStamp"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "타사 사이트에서 타임스탬프를 가져오기 위한 데이터를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.structs/timestamp/
---
**Inheritance:**
java.lang.Object
```
public class TimeStamp
```

타사 사이트에서 타임스탬프를 가져오기 위한 데이터를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [TimeStamp()](#TimeStamp--) |  |
|  | [TimeStamp(String url, String user, String password)](#TimeStamp-java.lang.String-java.lang.String-java.lang.String-) | 새 타임스탬프 구조를 인스턴스화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getUrl()](#getUrl--) | 타사 사이트의 URL. |
|
|  | [setUrl(String value)](#setUrl-java.lang.String-) | 타사 사이트의 URL. |
|
|  | [getUser()](#getUser--) | 사용자. |
|
|  | [setUser(String value)](#setUser-java.lang.String-) | 사용자. |
|
|  | [getPassword()](#getPassword--) | 비밀번호. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호. |
|
| [CloneTo(TimeStamp that)](#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
| [Clone()](#Clone--) |  |
| [clone()](#clone--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [hashCode()](#hashCode--) |  |
| [equals(TimeStamp obj1, TimeStamp obj2)](#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) |  |
### TimeStamp() {#TimeStamp--}
```
public TimeStamp()
```


### TimeStamp(String url, String user, String password) {#TimeStamp-java.lang.String-java.lang.String-java.lang.String-}
```
public TimeStamp(String url, String user, String password)
```


새 타임스탬프 구조를 인스턴스화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | url | java.lang.String | 타사 사이트의 URL. |
|
|  | user | java.lang.String | 사용자. |
|
|  | password | java.lang.String | 비밀번호. |
|

### getUrl() {#getUrl--}
```
public final String getUrl()
```


타사 사이트의 URL.


**Returns:**
java.lang.String
### setUrl(String value) {#setUrl-java.lang.String-}
```
public final void setUrl(String value)
```


타사 사이트의 URL.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getUser() {#getUser--}
```
public final String getUser()
```


사용자.


**Returns:**
java.lang.String
### setUser(String value) {#setUser-java.lang.String-}
```
public final void setUser(String value)
```


사용자.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


비밀번호.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


비밀번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### CloneTo(TimeStamp that) {#CloneTo-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public void CloneTo(TimeStamp that)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| that | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### Clone() {#Clone--}
```
public TimeStamp Clone()
```




**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### clone() {#clone--}
```
public Object clone()
```




**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 객체 | java.lang.Object |  |

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Returns:**
int
### equals(TimeStamp obj1, TimeStamp obj2) {#equals-com.groupdocs.signature.domain.structs.TimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public static boolean equals(TimeStamp obj1, TimeStamp obj2)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj1 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |
| obj2 | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

**Returns:**
boolean
