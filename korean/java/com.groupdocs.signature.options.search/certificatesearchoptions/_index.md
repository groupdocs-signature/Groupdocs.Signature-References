---
title: "CertificateSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "인증서 메타데이터 서명에 대한 검색 옵션을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.search/certificatesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class CertificateSearchOptions extends SearchOptions
```

인증서 메타데이터 서명에 대한 검색 옵션을 나타냅니다.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [CertificateSearchOptions()](#CertificateSearchOptions--) | TextSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [CertificateSearchOptions(String text)](#CertificateSearchOptions-java.lang.String-) | TextSearchOptions 클래스의 새 인스턴스를 텍스트 값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 검색 시 일치시킬 certificate 속성 텍스트를 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 검색 시 일치시킬 certificate 속성 텍스트를 지정합니다. |
|
|  | [getMatchType()](#getMatchType--) | 텍스트 일치 유형 검색을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 텍스트 일치 유형 검색을 가져오거나 설정합니다. |
|
### CertificateSearchOptions() {#CertificateSearchOptions--}
```
public CertificateSearchOptions()
```


TextSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### CertificateSearchOptions(String text) {#CertificateSearchOptions-java.lang.String-}
```
public CertificateSearchOptions(String text)
```


TextSearchOptions 클래스의 새 인스턴스를 텍스트 값으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 텍스트 서명의 텍스트를 설정합니다. |
|

### getText() {#getText--}
```
public final String getText()
```


검색 시 일치시킬 certificate 속성 텍스트를 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


검색 시 일치시킬 certificate 속성 텍스트를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


텍스트 일치 유형 검색을 가져오거나 설정합니다.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


텍스트 일치 유형 검색을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

