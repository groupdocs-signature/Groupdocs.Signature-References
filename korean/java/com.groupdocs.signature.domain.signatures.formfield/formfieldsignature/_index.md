---
title: "FormFieldSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "폼 필드 서명 속성을 포함합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.signatures.formfield/formfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class FormFieldSignature extends BaseSignature
```

폼 필드 서명 속성을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 고유한 폼 필드 이름을 지정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 고유한 폼 필드 이름을 지정합니다. |
|
|  | [getType()](#getType--) | 폼 필드 유형을 지정합니다. |
|
|  | [getValue()](#getValue--) | 폼 필드 데이터 객체를 지정합니다. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 폼 필드 데이터 객체를 지정합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | FormField Signature 인스턴스를 복제합니다. |
|
### getName() {#getName--}
```
public final String getName()
```


고유한 폼 필드 이름을 지정합니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


고유한 폼 필드 이름을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


폼 필드 유형을 지정합니다.


**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


폼 필드 데이터 객체를 지정합니다.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


폼 필드 데이터 객체를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

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

