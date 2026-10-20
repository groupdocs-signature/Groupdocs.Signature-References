---
title: "SearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서에서 서명을 추출하는 옵션을 나타냅니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.signature.options.search/searchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions)
```
public abstract class SearchOptions extends OptionsExtensions
```

문서에서 서명을 추출하는 옵션을 나타냅니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 검색을 위한 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 검색을 위한 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [getPagesSetup()](#getPagesSetup--) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 서명 검색을 위한 페이지를 지정하는 옵션입니다. |
|
|  | [getAllPages()](#getAllPages--) | 각 문서 페이지에서 검색하도록 하는 플래그입니다. |
|
|  | [setAllPages(boolean value)](#setAllPages-boolean-) | 각 문서 페이지에서 검색하도록 하는 플래그입니다. |
|
|  | [getSkipExternal()](#getSkipExternal--) | IsSignature로 표시된 서명만 반환하도록 하는 플래그입니다. |
|
|  | [setSkipExternal(boolean value)](#setSkipExternal-boolean-) | IsSignature로 표시된 서명만 반환하도록 하는 플래그입니다. |
|
|  | [getSearchPages(int totalPages)](#getSearchPages-int-) | 서명 추출을 위한 페이지 목록을 가져오는 가상 메서드입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


검색을 위한 문서 페이지 번호를 가져오거나 설정합니다.
값은 선택 사항입니다.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


검색을 위한 문서 페이지 번호를 가져오거나 설정합니다.
값은 선택 사항입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


서명 검색을 위한 페이지를 지정하는 옵션입니다.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


서명 검색을 위한 페이지를 지정하는 옵션입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getAllPages() {#getAllPages--}
```
public final boolean getAllPages()
```


각 문서 페이지에서 검색하도록 하는 플래그입니다. 기본값은 true로 설정됩니다.


**Returns:**
boolean
### setAllPages(boolean value) {#setAllPages-boolean-}
```
public final void setAllPages(boolean value)
```


각 문서 페이지에서 검색하도록 하는 플래그입니다. 기본값은 true로 설정됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSkipExternal() {#getSkipExternal--}
```
public final boolean getSkipExternal()
```


IsSignature로 표시된 서명만 반환하도록 하는 플래그입니다. 기본값은 false이며, 이는 지정된 기준과 일치하는 모든 서명을 반환함을 의미합니다.


**Returns:**
boolean
### setSkipExternal(boolean value) {#setSkipExternal-boolean-}
```
public final void setSkipExternal(boolean value)
```


IsSignature로 표시된 서명만 반환하도록 하는 플래그입니다. 기본값은 false이며, 이는 지정된 기준과 일치하는 모든 서명을 반환함을 의미합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSearchPages(int totalPages) {#getSearchPages-int-}
```
public System.Collections.Generic.List<Integer> getSearchPages(int totalPages)
```


서명 추출을 위한 페이지 목록을 가져오는 가상 메서드입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | totalPages | int | 페이지 총 수 |
|

**Returns:**
com.aspose.ms.System.Collections.Generic.List<java.lang.Integer> - 페이지 번호 목록

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
