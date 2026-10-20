---
title: "VerifyOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서를 검증하기 위한 옵션을 유지합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.options.verify/verifyoptions/
---
**Inheritance:**
java.lang.Object
```
public abstract class VerifyOptions
```

문서를 검증하기 위한 옵션을 유지합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [isValid()](#isValid--) | 유효한 속성 플래그. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 유효한 속성 플래그. |
|
|  | [getPageNumber()](#getPageNumber--) | 검증할 문서 페이지 번호. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 검증할 문서 페이지 번호. |
|
|  | [getPagesSetup()](#getPagesSetup--) | 검증할 페이지를 지정하는 페이지 옵션. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 검증할 페이지를 지정하는 페이지 옵션. |
|
|  | [getAllPages()](#getAllPages--) | 각 문서 페이지를 검증하는 플래그. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 각 문서 페이지를 검증하는 플래그. |
|
|  | [getExtensions()](#getExtensions--) | 대체 서명 옵션 검증을 위한 추가 확장. |
|
|  | [setExtensions(VerifyExtensions value)](#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-) | 대체 서명 옵션 검증을 위한 추가 확장. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### isValid() {#isValid--}
```
public final boolean isValid()
```


유효한 속성 플래그.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


유효한 속성 플래그.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPageNumber() {#getPageNumber--}
```
public Integer getPageNumber()
```


검증할 문서 페이지 번호. 속성이 설정되지 않으면 - 모든 페이지의
문서는 첫 번째 발생에 대해 검증됩니다.
최소값은 1입니다.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public void setPageNumber(Integer value)
```


검증할 문서 페이지 번호. 속성이 설정되지 않으면 - 모든 페이지의
문서는 첫 번째 발생에 대해 검증됩니다.
최소값은 1입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public PagesSetup getPagesSetup()
```


검증할 페이지를 지정하는 페이지 옵션.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public void setPagesSetup(PagesSetup value)
```


검증할 페이지를 지정하는 페이지 옵션.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


각 문서 페이지를 검증하는 플래그. 기본값은 true입니다.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


각 문서 페이지를 검증하는 플래그. 기본값은 true입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getExtensions() {#getExtensions--}
```
public final VerifyExtensions getExtensions()
```


대체 서명 옵션 검증을 위한 추가 확장.


**Returns:**
[VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions)
### setExtensions(VerifyExtensions value) {#setExtensions-com.groupdocs.signature.options.verifyextensions.VerifyExtensions-}
```
public final void setExtensions(VerifyExtensions value)
```


대체 서명 옵션 검증을 위한 추가 확장.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [VerifyExtensions](../../com.groupdocs.signature.options.verifyextensions/verifyextensions) |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
