---
title: "SearchResult"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "지정된 문서에서 서명을 검색한 결과입니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.domain/searchresult/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public class SearchResult implements Iterable<BaseSignature>
```

지정된 문서에서 서명을 검색한 결과입니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getProcessingTime()](#getProcessingTime--) | 검색 프로세스의 실행 시간을 밀리초 단위로 반환합니다. |
|
|  | [getTotalSignatures()](#getTotalSignatures--) | 검색 프로세스에 의해 처리된 전체 서명을 반환합니다. |
|
|  | [getSourceDocumentSize()](#getSourceDocumentSize--) | 원본 문서 크기를 반환합니다. |
|
|  | [getDestinDocumentSize()](#getDestinDocumentSize--) | 대상 문서 크기를 반환합니다. |
|
|  | [getSucceeded()](#getSucceeded--) | 찾은 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getFailed()](#getFailed--) | 검색 기준에 따라 검색 프로세스에 실패한 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [getSignatures()](#getSignatures--) | 감지된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). |
|
|  | [<T>toList(Class<T> typeOfT)](#-T-toList-java.lang.Class-T--) | 서명의 강력하게 형식화된 목록으로 변환을 제공합니다. |
|
| [updateContextData(SearchContext context, int documentType)](#updateContextData-com.groupdocs.signature.provider.SearchContext-int-) |  |
### getProcessingTime() {#getProcessingTime--}
```
public final long getProcessingTime()
```


검색 프로세스의 실행 시간을 밀리초 단위로 반환합니다.


**Returns:**
long
### getTotalSignatures() {#getTotalSignatures--}
```
public final int getTotalSignatures()
```


검색 프로세스에 의해 처리된 전체 서명을 반환합니다.


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


대상 문서 크기를 반환합니다. Search 메서드의 경우 항상 0을 반환합니다.


**Returns:**
long
### getSucceeded() {#getSucceeded--}
```
public final List<BaseSignature> getSucceeded()
```


찾은 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature). 이 목록은 항상 다음과 같을 것입니다
서명
(#getSignatures.getSignatures/#setSignatures(List).setSignatures(List)) 속성.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getFailed() {#getFailed--}
```
public final List<BaseSignature> getFailed()
```


검색 기준에 따라 검색 프로세스에 실패한 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).
현재 버전에서는 지원되지 않습니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### getSignatures() {#getSignatures--}
```
public final List<BaseSignature> getSignatures()
```


감지된 서명 목록 [BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature).


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.BaseSignature>
### <T>toList(Class<T> typeOfT) {#-T-toList-java.lang.Class-T--}
```
public final List<T> <T>toList(Class<T> typeOfT)
```


서명의 강력하게 형식화된 목록으로 변환을 제공합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
java.util.List<T> - 지정된 서명 유형의 목록을 반환합니다.


T
: 목록에 있는 서명의 유형입니다.

### updateContextData(SearchContext context, int documentType) {#updateContextData-com.groupdocs.signature.provider.SearchContext-int-}
```
public final void updateContextData(SearchContext context, int documentType)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| context | [SearchContext](../../com.groupdocs.signature.provider/searchcontext) |  |
| documentType | int |  |

