---
title: "TextFormFieldSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 문서용 텍스트 입력 폼 필드 서명 속성을 포함합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.domain.signatures.formfield/textformfieldsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.formfield.FormFieldSignature](../../com.groupdocs.signature.domain.signatures/formfield/formfieldsignature)
```
public final class TextFormFieldSignature extends FormFieldSignature
```

PDF 문서용 텍스트 입력 폼 필드 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextFormFieldSignature(String name)](#TextFormFieldSignature-java.lang.String-) | 미리 정의된 이름으로 PdfTextFormFieldSignature을 생성합니다. |
|
|  | [TextFormFieldSignature(String name, String text)](#TextFormFieldSignature-java.lang.String-java.lang.String-) | 미리 정의된 이름으로 PdfTextFormFieldSignature을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 폼 필드 텍스트 입력의 텍스트를 가져오거나 설정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 폼 필드 텍스트 입력의 텍스트를 가져오거나 설정합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | FormField Signature 인스턴스를 복제합니다. |
|
### TextFormFieldSignature(String name) {#TextFormFieldSignature-java.lang.String-}
```
public TextFormFieldSignature(String name)
```


미리 정의된 이름으로 PdfTextFormFieldSignature을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 폼 필드 객체의 이름. |
|

### TextFormFieldSignature(String name, String text) {#TextFormFieldSignature-java.lang.String-java.lang.String-}
```
public TextFormFieldSignature(String name, String text)
```


미리 정의된 이름으로 PdfTextFormFieldSignature을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 폼 필드 객체의 이름. |
|
|  | 텍스트 | java.lang.String | 폼 필드 객체의 텍스트. |
|

### getText() {#getText--}
```
public final String getText()
```


폼 필드 텍스트 입력의 텍스트를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


폼 필드 텍스트 입력의 텍스트를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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

