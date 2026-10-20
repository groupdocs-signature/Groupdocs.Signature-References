---
title: "FileLogger"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "로그 메시지를 파일에 기록합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.logging/filelogger/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.logging.ILogger](../../com.groupdocs.signature.logging/ilogger)
```
public class FileLogger implements ILogger
```

로그 메시지를 파일에 기록합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FileLogger(String fileName)](#FileLogger-java.lang.String-) | 파일에 로거를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [error(String message, Exception exception)](#error-java.lang.String-java.lang.Exception-) | 콘솔에 오류 메시지를 기록합니다. |
|
|  | [trace(String message)](#trace-java.lang.String-) | 콘솔에 추적 메시지를 기록합니다. |
|
|  | [warning(String message)](#warning-java.lang.String-) | 콘솔에 경고 메시지를 기록합니다; |
경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.
|
### FileLogger(String fileName) {#FileLogger-java.lang.String-}
```
public FileLogger(String fileName)
```


파일에 로거를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileName | java.lang.String | 전체 파일 이름 및 경로 |
|

### error(String message, Exception exception) {#error-java.lang.String-java.lang.Exception-}
```
public final void error(String message, Exception exception)
```


콘솔에 오류 메시지를 기록합니다.
오류 로그 메시지는 애플리케이션 흐름에서 복구할 수 없는 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 오류 메시지. |
|
|  | 예외 | java.lang.Exception | 예외. |
|

### trace(String message) {#trace-java.lang.String-}
```
public final void trace(String message)
```


콘솔에 추적 메시지를 기록합니다.
추적 로그 메시지는 애플리케이션 흐름에 대한 일반적으로 유용한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 추적 메시지. |
|

### warning(String message) {#warning-java.lang.String-}
```
public final void warning(String message)
```


콘솔에 경고 메시지를 기록합니다;
경고 로그 메시지는 애플리케이션 흐름에서 예상치 못한 복구 가능한 이벤트에 대한 정보를 제공합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 메시지 | java.lang.String | 경고 메시지. |
|

