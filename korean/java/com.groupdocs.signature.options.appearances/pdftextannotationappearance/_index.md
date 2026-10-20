---
title: "PdfTextAnnotationAppearance"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 텍스트 주석 객체의 Title, Subject, Content 외관을 설명합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.appearances/pdftextannotationappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class PdfTextAnnotationAppearance extends SignatureAppearance
```

PDF 텍스트 주석 객체(제목, 주제, 내용)의 외관을 설명합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfTextAnnotationAppearance()](#PdfTextAnnotationAppearance--) | PDF 서명 txt 주석 외관 객체를 생성합니다. |
|
|  | [PdfTextAnnotationAppearance(String title, String subject, String contents)](#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-) | 지정된 값(title, subject, contents)으로 PDF 서명 txt 주석을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getContents()](#getContents--) | 주석 객체의 content를 가져오거나 설정합니다. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | 주석 객체의 content를 가져오거나 설정합니다. |
|
|  | [getSubject()](#getSubject--) | 객체의 설명을 나타내는 Subject를 가져오거나 설정합니다. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 객체의 설명을 나타내는 Subject를 가져오거나 설정합니다. |
|
|  | [getTitle()](#getTitle--) | 주석 객체의 제목 표시줄에 표시될 Title을 가져오거나 설정합니다. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 주석 객체의 제목 표시줄에 표시될 Title을 가져오거나 설정합니다. |
|
|  | [getBorder()](#getBorder--) | 다양한 border 설정을 가져오거나 설정합니다 |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 다양한 border 설정을 가져오거나 설정합니다 |
|
|  | [getBorderEffect()](#getBorderEffect--) | border effect를 가져오거나 설정합니다. |
|
|  | [setBorderEffect(int value)](#setBorderEffect-int-) | border effect를 가져오거나 설정합니다. |
|
|  | [getBorderEffectIntensity()](#getBorderEffectIntensity--) | border effect intensity를 가져오거나 설정합니다. |
|
|  | [setBorderEffectIntensity(int value)](#setBorderEffectIntensity-int-) | border effect intensity를 가져오거나 설정합니다. |
|
|  | [getHCornerRadius()](#getHCornerRadius--) | horizontal corner radius를 가져오거나 설정합니다. |
|
|  | [setHCornerRadius(int value)](#setHCornerRadius-int-) | horizontal corner radius를 가져오거나 설정합니다. |
|
|  | [getVCornerRadius()](#getVCornerRadius--) | vertical corner radius를 가져오거나 설정합니다. |
|
|  | [setVCornerRadius(int value)](#setVCornerRadius-int-) | vertical corner radius를 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### PdfTextAnnotationAppearance() {#PdfTextAnnotationAppearance--}
```
public PdfTextAnnotationAppearance()
```


PDF 서명 txt 주석 외관 객체를 생성합니다.


### PdfTextAnnotationAppearance(String title, String subject, String contents) {#PdfTextAnnotationAppearance-java.lang.String-java.lang.String-java.lang.String-}
```
public PdfTextAnnotationAppearance(String title, String subject, String contents)
```


지정된 값(title, subject, contents)으로 PDF 서명 txt 주석을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | title | java.lang.String | Title. |
|
|  | subject | java.lang.String | Subject. |
|
|  | contents | java.lang.String | Contents. |
|

### getContents() {#getContents--}
```
public final String getContents()
```


주석 객체의 content를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


주석 객체의 content를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


객체의 설명을 나타내는 Subject를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


객체의 설명을 나타내는 Subject를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


주석 객체의 제목 표시줄에 표시될 Title을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


주석 객체의 제목 표시줄에 표시될 Title을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


다양한 border 설정을 가져오거나 설정합니다


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


다양한 border 설정을 가져오거나 설정합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getBorderEffect() {#getBorderEffect--}
```
public final int getBorderEffect()
```


border effect를 가져오거나 설정합니다.


**Returns:**
int
### setBorderEffect(int value) {#setBorderEffect-int-}
```
public final void setBorderEffect(int value)
```


border effect를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getBorderEffectIntensity() {#getBorderEffectIntensity--}
```
public final int getBorderEffectIntensity()
```


border effect intensity를 가져오거나 설정합니다. 값의 유효 범위는 [0..2]입니다.


**Returns:**
int
### setBorderEffectIntensity(int value) {#setBorderEffectIntensity-int-}
```
public final void setBorderEffectIntensity(int value)
```


border effect intensity를 가져오거나 설정합니다. 값의 유효 범위는 [0..2]입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHCornerRadius() {#getHCornerRadius--}
```
public final int getHCornerRadius()
```


horizontal corner radius를 가져오거나 설정합니다.


**Returns:**
int
### setHCornerRadius(int value) {#setHCornerRadius-int-}
```
public final void setHCornerRadius(int value)
```


horizontal corner radius를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getVCornerRadius() {#getVCornerRadius--}
```
public final int getVCornerRadius()
```


vertical corner radius를 가져오거나 설정합니다.


**Returns:**
int
### setVCornerRadius(int value) {#setVCornerRadius-int-}
```
public final void setVCornerRadius(int value)
```


vertical corner radius를 가져오거나 설정합니다.


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
