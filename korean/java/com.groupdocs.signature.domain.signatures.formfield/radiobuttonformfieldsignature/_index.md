---
title: "RadioButtonFormFieldSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "라디오버튼 입력 폼 필드 서명 속성을 포함합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.domain.signatures.formfield/radiobuttonformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class RadioButtonFormFieldSignature extends FormFieldSignature
```

라디오버튼 입력 폼 필드 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [RadioButtonFormFieldSignature(String name)](#RadioButtonFormFieldSignature-java.lang.String-) | 미리 정의된 이름으로 RadioButtonFieldSignature를 생성합니다. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--) | 미리 정의된 이름과 항목 목록으로 RadioButtonFieldSignature를 생성합니다. |
|
|  | [RadioButtonFormFieldSignature(String name, List<String> items, Object selected)](#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-) | 미리 정의된 이름, 항목 목록 및 선택된 값으로 RadioButtonFieldSignature를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSelected()](#getSelected--) | 선택된 값을 포함합니다. |
|
|  | [setSelected(String value)](#setSelected-java.lang.String-) | 선택된 값을 포함합니다. |
|
|  | [getItems()](#getItems--) | 라디오 버튼 옵션 목록을 가져오거나 설정합니다. |
|
|  | [setItems(List<String> value)](#setItems-java.util.List-java.lang.String--) | 라디오 버튼 옵션 목록을 가져오거나 설정합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | FormField Signature 인스턴스를 복제합니다. |
|
### RadioButtonFormFieldSignature(String name) {#RadioButtonFormFieldSignature-java.lang.String-}
```
public RadioButtonFormFieldSignature(String name)
```


미리 정의된 이름으로 RadioButtonFieldSignature를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 폼 필드 객체의 이름. |
|

### RadioButtonFormFieldSignature(String name, List<String> items) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--}
```
public RadioButtonFormFieldSignature(String name, List<String> items)
```


미리 정의된 이름과 항목 목록으로 RadioButtonFieldSignature를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 폼 필드 객체의 이름. |
|
|  | items | java.util.List<java.lang.String> | 라디오 버튼 목록의 값들. |
|

### RadioButtonFormFieldSignature(String name, List<String> items, Object selected) {#RadioButtonFormFieldSignature-java.lang.String-java.util.List-java.lang.String--java.lang.Object-}
```
public RadioButtonFormFieldSignature(String name, List<String> items, Object selected)
```


미리 정의된 이름, 항목 목록 및 선택된 값으로 RadioButtonFieldSignature를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 폼 필드 객체의 이름. |
|
|  | items | java.util.List<java.lang.String> | 라디오 버튼 목록의 값들. |
|
|  | selected | java.lang.Object | 선택된 값. |
|

### getSelected() {#getSelected--}
```
public final String getSelected()
```


선택된 값을 포함합니다.


**Returns:**
java.lang.String
### setSelected(String value) {#setSelected-java.lang.String-}
```
public final void setSelected(String value)
```


선택된 값을 포함합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getItems() {#getItems--}
```
public final List<String> getItems()
```


라디오 버튼 옵션 목록을 가져오거나 설정합니다.


**Returns:**
java.util.List<java.lang.String>
### setItems(List<String> value) {#setItems-java.util.List-java.lang.String--}
```
public final void setItems(List<String> value)
```


라디오 버튼 옵션 목록을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.String> |  |

### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 서명 | java.lang.Object | 비교할 서명 객체. |
|

**Returns:**
boolean - 전달된 서명 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - 서명 해시 코드

### deepClone() {#deepClone--}
```
public Object deepClone()
```


FormField Signature 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 FormField Signature 인스턴스를 반환합니다.

