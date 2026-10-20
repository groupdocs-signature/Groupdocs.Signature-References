---
title: "ProcessCompleteEventArgs"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 검증 및 검색 프로세스의 완료 이벤트에 대한 데이터를 제공합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.handler.events/processcompleteeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessCompleteEventArgs extends ProcessEventArgs
```

서명, 검증 및 검색 프로세스의 완료 이벤트에 대한 데이터를 제공합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCompleted()](#getCompleted--) | 프로세스 완료 시점을 나타냅니다. |
|
|  | [setCompleted(Date value)](#setCompleted-java.util.Date-) | 프로세스 완료 시점을 나타냅니다. |
|
|  | [getTicks()](#getTicks--) | 프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다. |
|
|  | [setTicks(long value)](#setTicks-long-) | 프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 처리된 서명의 총 수량을 나타냅니다. |
|
|  | [setTotalSignatures(int value)](#setTotalSignatures-int-) | 처리된 서명의 총 수량을 나타냅니다. |
|
|  | [getCanceled()](#getCanceled--) | 프로세스가 취소되었는지 여부를 나타냅니다. |
|
### getCompleted() {#getCompleted--}
```
public final Date getCompleted()
```


프로세스 완료 시점을 나타냅니다.


**Returns:**
java.util.Date
### setCompleted(Date value) {#setCompleted-java.util.Date-}
```
public final void setCompleted(Date value)
```


프로세스 완료 시점을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getTicks() {#getTicks--}
```
public final long getTicks()
```


프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다.


**Returns:**
long
### setTicks(long value) {#setTicks-long-}
```
public final void setTicks(long value)
```


프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


처리된 서명의 총 수량을 나타냅니다.


**Returns:**
int
### setTotalSignatures(int value) {#setTotalSignatures-int-}
```
public final void setTotalSignatures(int value)
```


처리된 서명의 총 수량을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getCanceled() {#getCanceled--}
```
public final boolean getCanceled()
```


프로세스가 취소되었는지 여부를 나타냅니다.


**Returns:**
boolean
