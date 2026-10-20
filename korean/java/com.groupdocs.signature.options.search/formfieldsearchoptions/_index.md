---
title: "FormFieldSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "양식 필드 서명에 대한 추상 검색 옵션을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.search/formfieldsearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class FormFieldSearchOptions extends SearchOptions
```

양식 필드 서명에 대한 추상 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [FormFieldSearchOptions()](#FormFieldSearchOptions--) | SearchFormFieldOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getType()](#getType--) | 검색해야 하는 경우 양식 필드 서명의 유형을 지정합니다. |
|
|  | [setType(Integer value)](#setType-java.lang.Integer-) | 검색해야 하는 경우 양식 필드 서명의 유형을 지정합니다. |
|
|  | [getName()](#getName--) | 검색해야 하는 경우 양식 필드 서명 이름의 정규식 패턴을 지정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 검색해야 하는 경우 양식 필드 서명 이름의 정규식 패턴을 지정합니다. |
|
|  | [getValue()](#getValue--) | 검색해야 하는 경우 양식 필드 서명의 값을 지정합니다. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 검색해야 하는 경우 양식 필드 서명의 값을 지정합니다. |
|
### FormFieldSearchOptions() {#FormFieldSearchOptions--}
```
public FormFieldSearchOptions()
```


SearchFormFieldOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### getType() {#getType--}
```
public final Integer getType()
```


검색해야 하는 경우 양식 필드 서명의 유형을 지정합니다. 기본값은 null입니다.


**Returns:**
java.lang.Integer
### setType(Integer value) {#setType-java.lang.Integer-}
```
public final void setType(Integer value)
```


검색해야 하는 경우 양식 필드 서명의 유형을 지정합니다. 기본값은 null입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getName() {#getName--}
```
public final String getName()
```


검색해야 하는 경우 양식 필드 서명 이름의 정규식 패턴을 지정합니다.
간단히 "text"처럼 사용하거나 "abc\\d+"와 같은 정규식을 사용할 수 있습니다. 기본값은 빈 문자열입니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


검색해야 하는 경우 양식 필드 서명 이름의 정규식 패턴을 지정합니다.
간단히 "text"처럼 사용하거나 "abc\\d+"와 같은 정규식을 사용할 수 있습니다. 기본값은 빈 문자열입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


검색해야 하는 경우 양식 필드 서명의 값을 지정합니다. 기본값은 null입니다.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


검색해야 하는 경우 양식 필드 서명의 값을 지정합니다. 기본값은 null입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

