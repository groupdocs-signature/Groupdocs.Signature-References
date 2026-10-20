---
title: "SignResult"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "새로 생성된 서명이 포함된 문서 서명 프로세스의 결과입니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.signature.domain/signresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class SignResult implements IResult
```

새로 생성된 서명이 포함된 문서 서명 프로세스의 결과입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 프로세스 실행 시간을 밀리초 단위로 반환합니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 전체 처리된 서명의 수를 반환합니다. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 원본 문서 크기를 반환합니다. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 대상 문서 크기를 반환합니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 새로 생성된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | 생성에 실패한 서명 목록. |
|
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


프로세스 실행 시간을 밀리초 단위로 반환합니다.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


전체 처리된 서명의 수를 반환합니다.


**Returns:**
int
### getSourceDocumentSize() {#getSourceDocumentSize--}
```
public final long getSourceDocumentSize()
```


원본 문서 크기를 반환합니다.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


대상 문서 크기를 반환합니다.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


새로 생성된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


생성에 실패한 서명 목록.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
