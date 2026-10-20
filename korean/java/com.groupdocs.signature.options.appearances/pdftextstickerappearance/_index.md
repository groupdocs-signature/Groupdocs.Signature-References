---
title: "PdfTextStickerAppearance"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 텍스트 주석 스티커 객체와 스티커의 팝업 창 외관을 설명합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.options.appearances/pdftextstickerappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public final class PdfTextStickerAppearance extends SignatureAppearance
```

PDF 텍스트 주석 스티커 객체와 스티커의 팝업 창 외관을 설명합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfTextStickerAppearance()](#PdfTextStickerAppearance--) | PDF 서명 텍스트 주석 모양 객체를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTitle()](#getTitle--) | 팝업 창의 제목을 가져오거나 설정합니다. |
|
|  | [setTitle(String value)](#setTitle-java.lang.String-) | 팝업 창의 제목을 가져오거나 설정합니다. |
|
|  | [getSubject()](#getSubject--) | 주제를 가져오거나 설정합니다. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 주제를 가져오거나 설정합니다. |
|
|  | [getContents()](#getContents--) | 팝업 창의 내용을 가져오거나 설정합니다. |
|
|  | [setContents(String value)](#setContents-java.lang.String-) | 팝업 창의 내용을 가져오거나 설정합니다. |
|
|  | [getOpened()](#getOpened--) | 스티커 팝업 창이 기본적으로 열릴지 설정합니다. |
|
|  | [setOpened(boolean value)](#setOpened-boolean-) | 스티커 팝업 창이 기본적으로 열릴지 설정합니다. |
|
|  | [getIcon()](#getIcon--) | 스티커의 아이콘을 가져오거나 설정합니다. |
|
|  | [setIcon(int value)](#setIcon-int-) | 스티커의 아이콘을 가져오거나 설정합니다. |
|
|  | [getDefaultAppearance()](#getDefaultAppearance--) | 스티커의 기본 외관을 가져옵니다. |
|
|  | [resetDefaultAppearance()](#resetDefaultAppearance--) | 스티커의 기본 외관 값을 지웁니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### PdfTextStickerAppearance() {#PdfTextStickerAppearance--}
```
public PdfTextStickerAppearance()
```


PDF 서명 텍스트 주석 모양 객체를 생성합니다.


### getTitle() {#getTitle--}
```
public final String getTitle()
```


팝업 창의 제목을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


팝업 창의 제목을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


주제를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


주제를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getContents() {#getContents--}
```
public final String getContents()
```


팝업 창의 내용을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setContents(String value) {#setContents-java.lang.String-}
```
public final void setContents(String value)
```


팝업 창의 내용을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getOpened() {#getOpened--}
```
public final boolean getOpened()
```


스티커 팝업 창이 기본적으로 열릴지 설정합니다.


**Returns:**
boolean
### setOpened(boolean value) {#setOpened-boolean-}
```
public final void setOpened(boolean value)
```


스티커 팝업 창이 기본적으로 열릴지 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getIcon() {#getIcon--}
```
public final int getIcon()
```


스티커의 아이콘을 가져오거나 설정합니다.


**Returns:**
int
### setIcon(int value) {#setIcon-int-}
```
public final void setIcon(int value)
```


스티커의 아이콘을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDefaultAppearance() {#getDefaultAppearance--}
```
public static PdfTextStickerAppearance getDefaultAppearance()
```


스티커의 기본 외관을 가져옵니다. 이러한 속성은 다음 경우 기본값으로 적용됩니다.
Options.SignatureAppearance 속성이 지정되지 않은 경우.
사용자는 언제든지 속성을 변경할 수 있습니다.


**Returns:**
[PdfTextStickerAppearance](../../com.groupdocs.signature.options.appearances/pdftextstickerappearance)
### resetDefaultAppearance() {#resetDefaultAppearance--}
```
public static void resetDefaultAppearance()
```


스티커의 기본 외관 값을 지웁니다.


### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
