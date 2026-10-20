---
title: "DeleteResult"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서에서 서명을 삭제한 결과입니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.domain/deleteresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.IResult](../../com.groupdocs.signature.domain/iresult)
```
public class DeleteResult implements IResult
```

문서에서 서명(들)을 삭제한 결과입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 프로세스 실행 시간을 밀리초 단위로 반환합니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 처리된 전체 서명을 반환합니다. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 원본 문서 크기를 반환합니다. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 업데이트된 문서 크기를 반환합니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 성공적으로 삭제된 서명의 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | 삭제되지 않은 서명의 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
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


처리된 전체 서명을 반환합니다.


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


업데이트된 문서 크기를 반환합니다.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


성공적으로 삭제된 서명의 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


삭제되지 않은 서명의 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
