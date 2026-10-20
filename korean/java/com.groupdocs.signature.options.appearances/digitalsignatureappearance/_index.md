---
title: "DigitalSignatureAppearance"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "디지털 서명을 위한 서명 라인의 외관을 설명합니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.options.appearances/digitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class DigitalSignatureAppearance extends SignatureAppearance
```

디지털 서명을 위한 서명 라인의 외관을 설명합니다.
하나의 Signature Line은 하나의 Digital Signature에만 적용될 수 있습니다.
Signature Line은 항상 첫 페이지에 있습니다.
이 기능은 .docx, .doc, .odt 및 .xlsx 파일 형식에 유용할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalSignatureAppearance()](#DigitalSignatureAppearance--) | Signature Line Appearance 객체를 생성합니다. |
|
|  | [DigitalSignatureAppearance(String signer, String title, String email)](#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-) | 지정된 값(서명자, 제목, 이메일)으로 Signature Line Appearance를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSigner()](#getSigner--) | 서명 라인의 서명자 이름을 가져오거나 설정합니다. |
|
|  | [setSigner(String value)](#setSigner-java.lang.String-) | 서명 라인의 서명자 이름을 가져오거나 설정합니다. |
|
|  | [getTitle()](#getTitle--) | 서명 라인의 제목을 가져오거나 설정합니다. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 서명 라인의 제목을 가져오거나 설정합니다. |
|
|  | [getEmail()](#getEmail--) | 서명 라인에 표시될 이메일을 가져오거나 설정합니다. |
|
|  | [setEmail(String value)](#setEmail-java.lang.String-) | 서명 라인에 표시될 이메일을 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### DigitalSignatureAppearance() {#DigitalSignatureAppearance--}
```
public DigitalSignatureAppearance()
```


Signature Line Appearance 객체를 생성합니다.


### DigitalSignatureAppearance(String signer, String title, String email) {#DigitalSignatureAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public DigitalSignatureAppearance(String signer, String title, String email)
```


지정된 값(서명자, 제목, 이메일)으로 Signature Line Appearance를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 서명자 | java.lang.String | 서명자 이름. |
|
|  | title | java.lang.String | 서명 제목. |
|
|  | 이메일 | java.lang.String | 작성자 이메일. |
|

### getSigner() {#getSigner--}
```
public final String getSigner()
```


서명 라인의 서명자 이름을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setSigner(String value) {#setSigner-java.lang.String-}
```
public final void setSigner(String value)
```


서명 라인의 서명자 이름을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


서명 라인의 제목을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


서명 라인의 제목을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getEmail() {#getEmail--}
```
public final String getEmail()
```


서명 라인에 표시될 이메일을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setEmail(String value) {#setEmail-java.lang.String-}
```
public final void setEmail(String value)
```


서명 라인에 표시될 이메일을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
