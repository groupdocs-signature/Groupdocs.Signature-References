---
title: "VerificationResult"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "검증 프로세스 결과를 보관하는 인스턴스입니다."
type: docs
weight: 20
url: /ko/java/com.groupdocs.signature.domain/verificationresult/
---
**Inheritance:**
java.lang.Object
```
public class VerificationResult
```

검증 프로세스 결과를 보관하는 인스턴스입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 프로세스 실행 시간을 밀리초 단위로 반환합니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 전체 처리된 서명의 수를 반환합니다. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 소스 문서 크기를 바이트 단위로 반환합니다. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 대상 문서 크기를 반환합니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 성공적으로 검증된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | 검증 과정에 실패한 서명 목록. |
|
|  | [isValid()](#isValid--) | 검증 과정이 성공했으면 true를, 그렇지 않으면 false를 반환합니다. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 검증 과정이 성공했으면 true를, 그렇지 않으면 false를 반환합니다. |
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


소스 문서 크기를 바이트 단위로 반환합니다.


**Returns:**
long
### getDestinDocumentSize() {#getDestinDocumentSize--}
```
public final long getDestinDocumentSize()
```


대상 문서 크기를 반환합니다. 검증의 경우 이 변수는 항상 0을 포함합니다.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


성공적으로 검증된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
현재 이 속성은 지원되지 않습니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


검증 과정에 실패한 서명 목록.
현재 이 속성은 지원되지 않습니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### isValid() {#isValid--}
```
public final boolean isValid()
```


검증 과정이 성공했으면 true를, 그렇지 않으면 false를 반환합니다.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


검증 과정이 성공했으면 true를, 그렇지 않으면 false를 반환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

