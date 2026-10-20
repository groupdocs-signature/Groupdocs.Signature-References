---
title: "ProcessProgressEventArgs"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 검증 및 검색 프로세스의 진행 중(OnProgress) 이벤트에 대한 데이터를 제공합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.handler.events/processprogresseventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs, [com.groupdocs.signature.handler.events.ProcessEventArgs](../../com.groupdocs.signature.handler.events/processeventargs)
```
public class ProcessProgressEventArgs extends ProcessEventArgs
```

서명, 검증 및 검색 프로세스의 OnProgress 이벤트에 대한 데이터를 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProcessProgressEventArgs()](#ProcessProgressEventArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProgress()](#getProgress--) | 진행률을 백분율로 나타냅니다. |
|
|  | [setProgress(int value)](#setProgress-int-) | 진행률을 백분율로 나타냅니다. |
|
|  | [getTicks()](#getTicks--) | 프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다. |
|
|  | [setTicks(long value)](#setTicks-long-) | 프로세스 시작 이벤트 이후 경과된 시간을 밀리초 단위로 나타냅니다. |
|
|  | [getProcessedSignatures()](#getProcessedSignatures--) | 처리된 서명의 수량을 나타냅니다. |
|
|  | [setProcessedSignatures(int value)](#setProcessedSignatures-int-) | 처리된 서명의 수량을 나타냅니다. |
|
|  | [getCancel()](#getCancel--) | 프로세스를 취소해야 하는지를 나타냅니다. |
|
|  | [setCancel(boolean value)](#setCancel-boolean-) | 프로세스를 취소해야 하는지를 나타냅니다. |
|
### ProcessProgressEventArgs() {#ProcessProgressEventArgs--}
```
public ProcessProgressEventArgs()
```


### getProgress() {#getProgress--}
```
public final int getProgress()
```


진행률을 백분율로 나타냅니다. 값 범위는 0에서 100까지입니다.


**Returns:**
int
### setProgress(int value) {#setProgress-int-}
```
public final void setProgress(int value)
```


진행률을 백분율로 나타냅니다. 값 범위는 0에서 100까지입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### getProcessedSignatures() {#getProcessedSignatures--}
```
public final int getProcessedSignatures()
```


처리된 서명의 수량을 나타냅니다.


**Returns:**
int
### setProcessedSignatures(int value) {#setProcessedSignatures-int-}
```
public final void setProcessedSignatures(int value)
```


처리된 서명의 수량을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getCancel() {#getCancel--}
```
public final boolean getCancel()
```


프로세스를 취소해야 하는지를 나타냅니다.


**Returns:**
boolean
### setCancel(boolean value) {#setCancel-boolean-}
```
public final void setCancel(boolean value)
```


프로세스를 취소해야 하는지를 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

