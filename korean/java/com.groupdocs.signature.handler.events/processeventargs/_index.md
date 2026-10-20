---
title: "ProcessEventArgs"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "서명 검증 및 검색 프로세스의 다양한 이벤트에 대한 데이터를 제공합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.handler.events/processeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ProcessEventArgs extends System.EventArgs
```

서명, 검증 및 검색 프로세스의 다양한 이벤트에 대한 데이터를 제공합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ProcessEventArgs()](#ProcessEventArgs--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFilePath()](#getFilePath--) | 문서 처리 파일 이름을 나타냅니다. |
|
|  | [setFilePath(String value)](#setFilePath-java.lang.String-) | 문서 처리 파일 이름을 나타냅니다. |
|
|  | [getStatus()](#getStatus--) | 현재 프로세스 상태를 나타냅니다. |
|
|  | [setStatus(int value)](#setStatus-int-) | 현재 프로세스 상태를 나타냅니다. |
|
### ProcessEventArgs() {#ProcessEventArgs--}
```
public ProcessEventArgs()
```


### getFilePath() {#getFilePath--}
```
public final String getFilePath()
```


문서 처리 파일 이름을 나타냅니다.


**Returns:**
java.lang.String
### setFilePath(String value) {#setFilePath-java.lang.String-}
```
public final void setFilePath(String value)
```


문서 처리 파일 이름을 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getStatus() {#getStatus--}
```
public final int getStatus()
```


현재 프로세스 상태를 나타냅니다.


**Returns:**
int
### setStatus(int value) {#setStatus-int-}
```
public final void setStatus(int value)
```


현재 프로세스 상태를 나타냅니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

