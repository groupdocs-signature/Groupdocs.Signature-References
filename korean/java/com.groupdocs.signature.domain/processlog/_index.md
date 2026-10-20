---
title: "ProcessLog"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 처리 세부 정보를 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.domain/processlog/
---
**Inheritance:**
java.lang.Object
```
public final class ProcessLog
```

문서 처리 세부 정보를 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDate()](#getDate--) | 프로세스 날짜와 시간을 가져옵니다. |
|
|  | [getType()](#getType--) | 프로세스 유형을 가져옵니다. |
|
|  | [getMessage()](#getMessage--) | 프로세스 설명을 가져옵니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 성공적으로 처리된 서명의 수. |
|
|  | [getFailed()](#getFailed--) | 처리 중 실패한 서명의 수. |
|
|  | [getSignatures()](#getSignatures--) | 성공적으로 처리된 서명 목록. |
|
### getDate() {#getDate--}
```
public final Date getDate()
```


프로세스 날짜와 시간을 가져옵니다.


**Returns:**
java.util.Date
### getType() {#getType--}
```
public final int getType()
```


프로세스 유형을 가져옵니다.


**Returns:**
int
### getMessage() {#getMessage--}
```
public final String getMessage()
```


프로세스 설명을 가져옵니다.


**Returns:**
java.lang.String
### getSucceeded() {#getSucceeded--}
```
public final int getSucceeded()
```


성공적으로 처리된 서명의 수.


**Returns:**
int
### getFailed() {#getFailed--}
```
public final int getFailed()
```


처리 중 실패한 서명의 수.


**Returns:**
int
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


성공적으로 처리된 서명 목록.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
