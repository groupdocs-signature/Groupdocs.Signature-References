---
title: "TextVerifyOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 텍스트 서명을 검증하기 위한 옵션을 유지합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.options.verify/textverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class TextVerifyOptions extends VerifyOptions
```

문서 텍스트 서명을 검증하기 위한 옵션을 유지합니다.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Text signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-text-signatures-in-the-document/)
* Advanced usage of settings of verification for Text signature with GroupDocs.Signature: /// [Advanced usage of eVerification Barcode signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-text-signatures/)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextVerifyOptions()](#TextVerifyOptions--) | TextVerifyOptions의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [TextVerifyOptions(String text)](#TextVerifyOptions-java.lang.String-) | TextVerifyOptions의 새 인스턴스를 검증 텍스트와 함께 초기화합니다. |
|
|  | [TextVerifyOptions(String text, int implementation)](#TextVerifyOptions-java.lang.String-int-) | 검증할 Text 속성과 서명 구현을 사용하여 TextVerifyOptions의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getText()](#getText--) | 검증해야 하는 경우 서명 텍스트를 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 검증해야 하는 경우 서명 텍스트를 지정합니다. |
|
|  | [getMatchType()](#getMatchType--) | 텍스트 일치 유형 검증을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 텍스트 일치 유형 검증을 가져오거나 설정합니다. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 검증할 서명의 유형. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | 검증할 서명의 유형. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | 검증할 양식 필드의 제목을 가져오거나 설정합니다. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | 검증할 양식 필드의 제목을 가져오거나 설정합니다. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | 검증할 양식 필드의 유형을 가져오거나 설정합니다. |
|
|  | [setFormTextFieldType(Integer value)](#setFormTextFieldType-java.lang.Integer-) | 검증할 양식 필드의 유형을 가져오거나 설정합니다. |
|
|  | [getSignatureID()](#getSignatureID--) | 검증해야 하는 경우 0보다 큰 텍스트 서명 ID를 지정합니다. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 검증해야 하는 경우 0보다 큰 텍스트 서명 ID를 지정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### TextVerifyOptions() {#TextVerifyOptions--}
```
public TextVerifyOptions()
```


TextVerifyOptions의 새 인스턴스를 기본값으로 초기화합니다.


### TextVerifyOptions(String text) {#TextVerifyOptions-java.lang.String-}
```
public TextVerifyOptions(String text)
```


TextVerifyOptions의 새 인스턴스를 검증 텍스트와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 검증할 텍스트 |
|

### TextVerifyOptions(String text, int implementation) {#TextVerifyOptions-java.lang.String-int-}
```
public TextVerifyOptions(String text, int implementation)
```


검증할 Text 속성과 서명 구현을 사용하여 TextVerifyOptions의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 검증할 텍스트. |
|
|  | 구현 | int | 서명 구현 유형. |
|

### getText() {#getText--}
```
public final String getText()
```


검증해야 하는 경우 서명 텍스트를 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


검증해야 하는 경우 서명 텍스트를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


텍스트 일치 유형 검증을 가져오거나 설정합니다.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


텍스트 일치 유형 검증을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


검증할 서명의 유형.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


검증할 서명의 유형.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


검증할 양식 필드의 제목을 가져오거나 설정합니다.
이 속성에 설정된 텍스트는 텍스트 양식 필드에서만 찾을 수 있습니다.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


검증할 양식 필드의 제목을 가져오거나 설정합니다.
이 속성에 설정된 텍스트는 텍스트 양식 필드에서만 찾을 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final Integer getFormTextFieldType()
```


검증할 양식 필드의 유형을 가져오거나 설정합니다.
이 속성에 설정된 텍스트는 텍스트 양식 필드에서만 찾을 수 있습니다.


**Returns:**
java.lang.Integer
### setFormTextFieldType(Integer value) {#setFormTextFieldType-java.lang.Integer-}
```
public final void setFormTextFieldType(Integer value)
```


검증할 양식 필드의 유형을 가져오거나 설정합니다.
이 속성에 설정된 텍스트는 텍스트 양식 필드에서만 찾을 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


검증이 필요하면 텍스트 서명 ID를 0보다 크게 지정하십시오. 이 속성은 PDF 문서에서만 지원됩니다.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


검증이 필요하면 텍스트 서명 ID를 0보다 크게 지정하십시오. 이 속성은 PDF 문서에서만 지원됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
