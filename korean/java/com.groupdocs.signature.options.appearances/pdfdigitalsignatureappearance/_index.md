---
title: "PdfDigitalSignatureAppearance"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 문서에서 디지털 서명의 외관을 설명합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.appearances/pdfdigitalsignatureappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfDigitalSignatureAppearance extends SignatureAppearance
```

PDF 문서에서 디지털 서명의 외관을 설명합니다.

<br />

*** ** * ** ***

**Learn more**

* See more simple examples on creating digital electronic signatures with GroupDocs.Signature: [Advanced signing document with Digital electronic signatures](../https://docs.groupdocs.com/signature/java/sign-document-with-digital-signature-advanced/)
* See more advanced examples of settings of various electronic signature with GroupDocs.Signature: [Advanced electronic signatures properties](../https://docs.groupdocs.com/signature/java/sign-documents-with-extra-digital-signature-properties/)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfDigitalSignatureAppearance()](#PdfDigitalSignatureAppearance--) | 기본값으로 서명 모양 개체를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getContactInfoLabel()](#getContactInfoLabel--) | 연락처 정보 레이블을 가져오거나 설정합니다. |
|
|  | [setContactInfoLabel(String value)](#setContactInfoLabel-java.lang.String-) | 연락처 정보 레이블을 가져오거나 설정합니다. |
|
|  | [getReasonLabel()](#getReasonLabel--) | 이유 레이블을 가져오거나 설정합니다. |
|
|  | [setReasonLabel(String value)](#setReasonLabel-java.lang.String-) | 이유 레이블을 가져오거나 설정합니다. |
|
|  | [getLocationLabel()](#getLocationLabel--) | 위치 레이블을 가져오거나 설정합니다. |
|
|  | [setLocationLabel(String value)](#setLocationLabel-java.lang.String-) | 위치 레이블을 가져오거나 설정합니다. |
|
|  | [getDigitalSignedLabel()](#getDigitalSignedLabel--) | 디지털 서명 레이블을 가져오거나 설정합니다. |
|
|  | [setDigitalSignedLabel(String value)](#setDigitalSignedLabel-java.lang.String-) | 디지털 서명 레이블을 가져오거나 설정합니다. |
|
|  | [getDateSignedAtLabel()](#getDateSignedAtLabel--) | 서명 날짜 레이블을 가져오거나 설정합니다. |
|
|  | [setDateSignedAtLabel(String value)](#setDateSignedAtLabel-java.lang.String-) | 서명 날짜 레이블을 가져오거나 설정합니다. |
|
|  | [getBackground()](#getBackground--) | 서명 모양의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setBackground(Color value)](#setBackground-java.awt.Color-) | 서명 모양의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setBackground(String value)](#setBackground-java.lang.String-) | 서명 모양의 배경 색상을 가져오거나 설정합니다. |
|
|  | [getFontFamilyName()](#getFontFamilyName--) | 레이블을 표시할 글꼴 패밀리 이름을 가져오거나 설정합니다. |
|
|  | [setFontFamilyName(String value)](#setFontFamilyName-java.lang.String-) | 레이블을 표시할 글꼴 패밀리 이름을 가져오거나 설정합니다. |
|
|  | [getFontSize()](#getFontSize--) | 레이블을 표시할 글꼴 크기를 가져오거나 설정합니다. |
|
|  | [setFontSize(double value)](#setFontSize-double-) | 레이블을 표시할 글꼴 크기를 가져오거나 설정합니다. |
|
|  | [getForeground()](#getForeground--) | 서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다. |
|
|  | [setForeground(Color value)](#setForeground-java.awt.Color-) | 서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다. |
|
|  | [setForeground(String value)](#setForeground-java.lang.String-) | 서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다. |
|
### PdfDigitalSignatureAppearance() {#PdfDigitalSignatureAppearance--}
```
public PdfDigitalSignatureAppearance()
```


기본값으로 서명 모양 개체를 생성합니다.


### getContactInfoLabel() {#getContactInfoLabel--}
```
public final String getContactInfoLabel()
```


연락처 정보 레이블을 가져오거나 설정합니다. 기본값: "Contact".
이 값이 비어 있으면 디지털 서명 영역에 연락처 레이블이 표시되지 않습니다.


**Returns:**
java.lang.String
### setContactInfoLabel(String value) {#setContactInfoLabel-java.lang.String-}
```
public final void setContactInfoLabel(String value)
```


연락처 정보 레이블을 가져오거나 설정합니다. 기본값: "Contact".
이 값이 비어 있으면 디지털 서명 영역에 연락처 레이블이 표시되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getReasonLabel() {#getReasonLabel--}
```
public final String getReasonLabel()
```


이유 레이블을 가져오거나 설정합니다. 기본값: "Reason".
이 값이 비어 있으면 디지털 서명 영역에 이유 레이블이 표시되지 않습니다.


**Returns:**
java.lang.String
### setReasonLabel(String value) {#setReasonLabel-java.lang.String-}
```
public final void setReasonLabel(String value)
```


이유 레이블을 가져오거나 설정합니다. 기본값: "Reason".
이 값이 비어 있으면 디지털 서명 영역에 이유 레이블이 표시되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLocationLabel() {#getLocationLabel--}
```
public final String getLocationLabel()
```


위치 레이블을 가져오거나 설정합니다. 기본값: "Location".
이 값이 비어 있으면 디지털 서명 영역에 위치 레이블이 표시되지 않습니다.


**Returns:**
java.lang.String
### setLocationLabel(String value) {#setLocationLabel-java.lang.String-}
```
public final void setLocationLabel(String value)
```


위치 레이블을 가져오거나 설정합니다. 기본값: "Location".
이 값이 비어 있으면 디지털 서명 영역에 위치 레이블이 표시되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getDigitalSignedLabel() {#getDigitalSignedLabel--}
```
public final String getDigitalSignedLabel()
```


디지털 서명 레이블을 가져오거나 설정합니다. 기본값: "Digitally signed by".


**Returns:**
java.lang.String
### setDigitalSignedLabel(String value) {#setDigitalSignedLabel-java.lang.String-}
```
public final void setDigitalSignedLabel(String value)
```


디지털 서명 레이블을 가져오거나 설정합니다. 기본값: "Digitally signed by".


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getDateSignedAtLabel() {#getDateSignedAtLabel--}
```
public final String getDateSignedAtLabel()
```


서명 날짜 레이블을 가져오거나 설정합니다. 기본값: "Date".


**Returns:**
java.lang.String
### setDateSignedAtLabel(String value) {#setDateSignedAtLabel-java.lang.String-}
```
public final void setDateSignedAtLabel(String value)
```


서명 날짜 레이블을 가져오거나 설정합니다. 기본값: "Date".


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getBackground() {#getBackground--}
```
public final Color getBackground()
```


서명 모양의 배경 색상을 가져오거나 설정합니다.
기본값은 SystemColors.Windows입니다.


**Returns:**
java.awt.Color
### setBackground(Color value) {#setBackground-java.awt.Color-}
```
public final void setBackground(Color value)
```


서명 모양의 배경 색상을 가져오거나 설정합니다.
기본값은 SystemColors.Windows입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setBackground(String value) {#setBackground-java.lang.String-}
```
public final void setBackground(String value)
```


서명 모양의 배경 색상을 가져오거나 설정합니다.
기본값은 SystemColors.Windows입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFontFamilyName() {#getFontFamilyName--}
```
public final String getFontFamilyName()
```


레이블을 표시할 글꼴 패밀리 이름을 가져오거나 설정합니다. 기본값은 "Arial"입니다.


**Returns:**
java.lang.String
### setFontFamilyName(String value) {#setFontFamilyName-java.lang.String-}
```
public final void setFontFamilyName(String value)
```


레이블을 표시할 글꼴 패밀리 이름을 가져오거나 설정합니다. 기본값은 "Arial"입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFontSize() {#getFontSize--}
```
public final double getFontSize()
```


레이블을 표시할 글꼴 크기를 가져오거나 설정합니다. 기본값은 10입니다.


**Returns:**
double
### setFontSize(double value) {#setFontSize-double-}
```
public final void setFontSize(double value)
```


레이블을 표시할 글꼴 크기를 가져오거나 설정합니다. 기본값은 10입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getForeground() {#getForeground--}
```
public final Color getForeground()
```


서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다.
기본적으로 값은 Color.FromArgb(76, 100, 255) 입니다


**Returns:**
java.awt.Color
### setForeground(Color value) {#setForeground-java.awt.Color-}
```
public final void setForeground(Color value)
```


서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다.
기본적으로 값은 Color.FromArgb(76, 100, 255) 입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setForeground(String value) {#setForeground-java.lang.String-}
```
public final void setForeground(String value)
```


서명 모양의 전경 텍스트 색상을 가져오거나 설정합니다.
기본적으로 값은 Color.FromArgb(76, 100, 255) 입니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

