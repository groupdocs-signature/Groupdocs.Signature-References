---
title: "TextSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "텍스트 서명 속성을 포함합니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.signature.domain.signatures/textsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class TextSignature extends BaseSignature
```

텍스트 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextSignature(String signatureId)](#TextSignature-java.lang.String-) | 검색 과정 후에 얻은 서명 식별자를 사용하여 TextSignature 객체를 초기화합니다. |
|
| [TextSignature()](#TextSignature--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 서명에 포함된 텍스트를 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 서명에 포함된 텍스트를 지정합니다. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 텍스트 서명 구현을 지정합니다. |
|
|  | [getNative()](#getNative--) | 네이티브 속성을 지정합니다. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | 네이티브 속성을 지정합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | 텍스트 서명 인스턴스를 복제합니다. |
|
### TextSignature(String signatureId) {#TextSignature-java.lang.String-}
```
public TextSignature(String signatureId)
```


검색 과정 후에 얻은 서명 식별자를 사용하여 TextSignature 객체를 초기화합니다.
이 고유 식별자는 문서 서명 정보 레이어에서 이 서명의 추가 속성을 찾는 데 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 서명 또는 검색 방법으로 얻은 고유 서명 식별자입니다. |
|

### TextSignature() {#TextSignature--}
```
public TextSignature()
```


### getText() {#getText--}
```
public final String getText()
```


서명에 포함된 텍스트를 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


서명에 포함된 텍스트를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


텍스트 서명 구현을 지정합니다.


**Returns:**
int
### getNative() {#getNative--}
```
public final boolean getNative()
```


네이티브 속성을 지정합니다. 서명이 문서별인 경우 true입니다.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


네이티브 속성을 지정합니다. 서명이 문서별인 경우 true입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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


텍스트 서명 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 텍스트 서명 인스턴스를 반환합니다.

