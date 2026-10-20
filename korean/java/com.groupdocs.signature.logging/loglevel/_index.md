---
title: "LogLevel"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "SignatureSettings에 설정된 로거에 전달되는 메시지 종류를 지정합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.logging/loglevel/
---
**Inheritance:**
java.lang.Object
```
public final class LogLevel
```

설정된 로거에 전달되는 메시지 종류를 지정합니다
SignatureSettings
.
값은 플래그이며 예를 들어 결합할 수 있습니다
LogLevel.Error \| LogLevel.Warning
.

## 필드

| 필드 | 설명 |
| --- | --- |
|  | [None](#None) | 아무 것도 기록되지 않습니다. |
|
|  | [Error](#Error) | 오류: 작업이 실패했습니다. |
|
|  | [Warning](#Warning) | 경고: 작업은 성공했지만 결과가 예상과 다를 수 있습니다. |
|
|  | [Trace](#Trace) | 추적: 작업의 단계로, 시작 및 종료와 같습니다. |
|
|  | [All](#All) | 오류, 경고 및 추적. |
|
### None {#None}
```
public static final int None
```


아무 것도 기록되지 않습니다.


### Error {#Error}
```
public static final int Error
```


오류: 작업이 실패했습니다.


### Warning {#Warning}
```
public static final int Warning
```


경고: 작업은 성공했지만 결과가 예상과 다를 수 있습니다.


### Trace {#Trace}
```
public static final int Trace
```


추적: 작업의 단계로, 시작 및 종료와 같습니다.


### All {#All}
```
public static final int All
```


오류, 경고 및 추적. 이것이 기본값입니다.


