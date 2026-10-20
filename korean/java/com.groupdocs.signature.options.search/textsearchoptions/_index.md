---
title: "TextSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "텍스트 서명에 대한 검색 옵션을 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.signature.options.search/textsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class TextSearchOptions extends SearchOptions
```

텍스트 서명에 대한 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextSearchOptions()](#TextSearchOptions--) | TextSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [TextSearchOptions(String text)](#TextSearchOptions-java.lang.String-) | TextSearchOptions 클래스의 새 인스턴스를 텍스트 값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 검색 시 일치시킬 서명 텍스트를 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 검색 시 일치시킬 서명 텍스트를 지정합니다. |
|
|  | [getMatchType()](#getMatchType--) | 텍스트 일치 유형 검색을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 텍스트 일치 유형 검색을 가져오거나 설정합니다. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 검색할 텍스트 서명 구현을 지정합니다. |
|
|  | [setSignatureImplementation(Integer value)](#setSignatureImplementation-java.lang.Integer-) | 검색할 텍스트 서명 구현을 지정합니다. |
|
### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```


TextSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### TextSearchOptions(String text) {#TextSearchOptions-java.lang.String-}
```
public TextSearchOptions(String text)
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


검색 시 일치시킬 서명 텍스트를 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


검색 시 일치시킬 서명 텍스트를 지정합니다.


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

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final Integer getSignatureImplementation()
```


검색할 텍스트 서명 구현을 지정합니다.


**Returns:**
java.lang.Integer
### setSignatureImplementation(Integer value) {#setSignatureImplementation-java.lang.Integer-}
```
public final void setSignatureImplementation(Integer value)
```


검색할 텍스트 서명 구현을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

