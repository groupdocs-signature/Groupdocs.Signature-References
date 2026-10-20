---
title: "ProcessStartEventArgs"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 검증 및 검색 프로세스의 시작 이벤트에 대한 데이터를 제공합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.handler.events/processstarteventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessStartEventArgs extends ProcessEventArgs
```

서명, 검증 및 검색 프로세스의 시작 이벤트에 대한 데이터를 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProcessStartEventArgs()](#ProcessStartEventArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStarted()](#getStarted--) | 프로세스 시작 시점을 나타냅니다. |
|
|  | [setStarted(Date value)](#setStarted-java.util.Date-) | 프로세스 시작 시점을 나타냅니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 처리될 서명의 총 수량을 나타냅니다. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | 처리될 서명의 총 수량을 나타냅니다. |
|
### ProcessStartEventArgs() {#ProcessStartEventArgs--}
```
public ProcessStartEventArgs()
```


### getStarted() {#getStarted--}
```
public final Date getStarted()
```


프로세스 시작 시점을 나타냅니다.


**Returns:**
java.util.Date
### setStarted(Date value) {#setStarted-java.util.Date-}
```
public final void setStarted(Date value)
```


프로세스 시작 시점을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


처리될 서명의 총 수량을 나타냅니다.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


처리될 서명의 총 수량을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

