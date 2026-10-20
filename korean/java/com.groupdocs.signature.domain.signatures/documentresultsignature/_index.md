---
title: "DocumentResultSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "새로 생성된 서명이 포함된 문서에 대한 아카이브 문서 서명 처리 결과입니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.signatures/documentresultsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DocumentResultSignature extends BaseSignature
```

새로 생성된 서명이 포함된 문서에 대한 아카이브 문서 서명 처리 결과입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileName()](#getFileName--) | 문서 파일 이름 |
|
|  | [getProcessingTime()](#getProcessingTime--) | 프로세스 실행 시간을 밀리초 단위로 반환합니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 전체 처리된 서명의 수를 반환합니다. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 원본 문서 크기를 반환합니다. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 대상 문서 크기를 반환합니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 성공적으로 처리된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | 프로세스 중에 실패한 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getErrorMessage()](#getErrorMessage--) | 문서가 오류와 함께 처리된 경우 이 속성에 오류 메시지가 포함됩니다. |
|
### getFileName() {#getFileName--}
```
public final String getFileName()
```


문서 파일 이름


**Returns:**
java.lang.String
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


성공적으로 처리된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


프로세스 중에 실패한 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getErrorMessage() {#getErrorMessage--}
```
public final String getErrorMessage()
```


문서가 오류와 함께 처리된 경우 이 속성에 오류 메시지가 포함됩니다.


**Returns:**
java.lang.String
