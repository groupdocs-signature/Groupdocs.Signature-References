---
title: "StampLine"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스탬프 라인 속성을 지정합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.stamps/stampline/
---
**Inheritance:**
java.lang.Object
```
public class StampLine
```

스탬프 라인 속성을 지정합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [StampLine()](#StampLine--) | 기본값으로 StampLine을 생성합니다. |
|
|  | [StampLine(String text)](#StampLine-java.lang.String-) | 텍스트와 함께 StampLine을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getHeight()](#getHeight--) | Stamp의 줄 높이를 가져오거나 설정합니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | Stamp의 줄 높이를 가져오거나 설정합니다. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setBackgroundColor(String value)](#setBackgroundColor-java.lang.String-) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [getText()](#getText--) | 스탬프 라인의 텍스트를 가져오거나 설정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 스탬프 라인의 텍스트를 가져오거나 설정합니다. |
|
|  | [getFont()](#getFont--) | Stamp 라인 텍스트의 글꼴을 가져오거나 설정합니다. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | Stamp 라인 텍스트의 글꼴을 가져오거나 설정합니다. |
|
|  | [getTextColor()](#getTextColor--) | 서명의 텍스트 색상을 가져오거나 설정합니다. |
|
|  | [setTextColor(Color value)](#setTextColor-java.awt.Color-) | 서명의 텍스트 색상을 가져오거나 설정합니다. |
|
|  | [setTextColor(String value)](#setTextColor-java.lang.String-) | 서명의 텍스트 색상을 가져오거나 설정합니다. |
|
|  | [getTextBottomIntent()](#getTextBottomIntent--) | 텍스트의 아래쪽 의도를 가져오거나 설정합니다. |
|
|  | [setTextBottomIntent(int value)](#setTextBottomIntent-int-) | 텍스트의 아래쪽 의도를 가져오거나 설정합니다. |
|
|  | [getTextRepeatType()](#getTextRepeatType--) | 텍스트 반복 유형을 가져오거나 설정합니다. |
|
|  | [setTextRepeatType(int value)](#setTextRepeatType-int-) | 텍스트 반복 유형을 가져오거나 설정합니다. |
|
|  | [getOuterBorder()](#getOuterBorder--) | 외부 테두리를 설정합니다. |
|
|  | [setOuterBorder(Border value)](#setOuterBorder-com.groupdocs.signature.domain.Border-) | 외부 테두리를 설정합니다. |
|
|  | [getInnerBorder()](#getInnerBorder--) | 내부 테두리를 설정합니다. |
|
|  | [setInnerBorder(Border value)](#setInnerBorder-com.groupdocs.signature.domain.Border-) | 내부 테두리를 설정합니다. |
|
|  | [getVisible()](#getVisible--) | Stamp 라인의 가시성을 가져오고 설정합니다. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | Stamp 라인의 가시성을 가져오고 설정합니다. |
|
### StampLine() {#StampLine--}
```
public StampLine()
```


기본값으로 StampLine을 생성합니다.


### StampLine(String text) {#StampLine-java.lang.String-}
```
public StampLine(String text)
```


텍스트와 함께 StampLine을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | Stamp 라인의 텍스트. |
|

### getHeight() {#getHeight--}
```
public final int getHeight()
```


Stamp의 줄 높이를 가져오거나 설정합니다.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


Stamp의 줄 높이를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```


서명의 배경 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setBackgroundColor(Color value) {#setBackgroundColor-java.awt.Color-}
```
public final void setBackgroundColor(Color value)
```


서명의 배경 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setBackgroundColor(String value) {#setBackgroundColor-java.lang.String-}
```
public final void setBackgroundColor(String value)
```


서명의 배경 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getText() {#getText--}
```
public final String getText()
```


스탬프 라인의 텍스트를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


스탬프 라인의 텍스트를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


Stamp 라인 텍스트의 글꼴을 가져오거나 설정합니다.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


Stamp 라인 텍스트의 글꼴을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getTextColor() {#getTextColor--}
```
public final Color getTextColor()
```


서명의 텍스트 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setTextColor(Color value) {#setTextColor-java.awt.Color-}
```
public final void setTextColor(Color value)
```


서명의 텍스트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setTextColor(String value) {#setTextColor-java.lang.String-}
```
public final void setTextColor(String value)
```


서명의 텍스트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTextBottomIntent() {#getTextBottomIntent--}
```
public final int getTextBottomIntent()
```


텍스트의 아래쪽 의도를 가져오거나 설정합니다.


**Returns:**
int
### setTextBottomIntent(int value) {#setTextBottomIntent-int-}
```
public final void setTextBottomIntent(int value)
```


텍스트의 아래쪽 의도를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTextRepeatType() {#getTextRepeatType--}
```
public final int getTextRepeatType()
```


텍스트 반복 유형을 가져오거나 설정합니다.


**Returns:**
int
### setTextRepeatType(int value) {#setTextRepeatType-int-}
```
public final void setTextRepeatType(int value)
```


텍스트 반복 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getOuterBorder() {#getOuterBorder--}
```
public final Border getOuterBorder()
```


외부 테두리를 설정합니다.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setOuterBorder(Border value) {#setOuterBorder-com.groupdocs.signature.domain.Border-}
```
public final void setOuterBorder(Border value)
```


외부 테두리를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getInnerBorder() {#getInnerBorder--}
```
public final Border getInnerBorder()
```


내부 테두리를 설정합니다.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setInnerBorder(Border value) {#setInnerBorder-com.groupdocs.signature.domain.Border-}
```
public final void setInnerBorder(Border value)
```


내부 테두리를 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


Stamp 라인의 가시성을 가져오고 설정합니다.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


Stamp 라인의 가시성을 가져오고 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

