---
title: "TextShadow"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "텍스트 서명을 위한 텍스트 그림자 속성을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain.extensions.signoptions/textshadow/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class TextShadow extends SignatureExtension
```

텍스트 서명을 위한 텍스트 그림자 속성을 나타냅니다.
결과는 서명 유형 및 문서 형식에 따라 달라질 수 있습니다.
TextShadow는 모든 지원되는 문서 유형에 대해 TextAsImage 서명과 함께 사용할 것을 권장합니다,
또한 Cells(.xslx) 및 Slides(.pptx)용 간단한 TextSignature와 워터마크로서의 TextSignature에도 적용됩니다.
Words(.docx)용 간단한 TextSignature도 권장되지만 기능이 제한적입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextShadow()](#TextShadow--) | 기본 옵션으로 TextShadow를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDistance()](#getDistance--) | 텍스트와 그림자 사이의 거리를 가져오거나 설정합니다. |
|
|  | [setDistance(double value)](#setDistance-double-) | 텍스트와 그림자 사이의 거리를 가져오거나 설정합니다. |
|
|  | [getAngle()](#getAngle--) | 텍스트에 대한 그림자 배치 각도를 가져오거나 설정합니다. |
|
|  | [setAngle(double value)](#setAngle-double-) | 텍스트에 대한 그림자 배치 각도를 가져오거나 설정합니다. |
|
|  | [getColor()](#getColor--) | 그림자의 색상을 가져오거나 설정합니다. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 그림자의 색상을 가져오거나 설정합니다. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 그림자의 색상을 가져오거나 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 그림자의 투명도를 가져오거나 설정합니다. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 그림자의 투명도를 가져오거나 설정합니다. |
|
|  | [getBlur()](#getBlur--) | 그림자의 흐림 정도를 가져오거나 설정합니다. |
|
|  | [setBlur(double value)](#setBlur-double-) | 그림자의 흐림 정도를 가져오거나 설정합니다. |
|
### TextShadow() {#TextShadow--}
```
public TextShadow()
```


기본 옵션으로 TextShadow를 생성합니다.


### getDistance() {#getDistance--}
```
public final double getDistance()
```


텍스트와 그림자 사이의 거리를 가져오거나 설정합니다.
기본값은 1입니다.


**Returns:**
double
### setDistance(double value) {#setDistance-double-}
```
public final void setDistance(double value)
```


텍스트와 그림자 사이의 거리를 가져오거나 설정합니다.
기본값은 1입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getAngle() {#getAngle--}
```
public final double getAngle()
```


텍스트에 대한 그림자 배치 각도를 가져오거나 설정합니다.
기본값은 0입니다.


**Returns:**
double
### setAngle(double value) {#setAngle-double-}
```
public final void setAngle(double value)
```


텍스트에 대한 그림자 배치 각도를 가져오거나 설정합니다.
기본값은 0입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


그림자의 색상을 가져오거나 설정합니다.
기본값은 검정색입니다.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


그림자의 색상을 가져오거나 설정합니다.
기본값은 검정색입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


그림자의 색상을 가져오거나 설정합니다.
기본값은 검정색입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


그림자의 투명도를 가져오거나 설정합니다.
기본값은 0입니다.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


그림자의 투명도를 가져오거나 설정합니다.
기본값은 0입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getBlur() {#getBlur--}
```
public final double getBlur()
```


그림자의 흐림 정도를 가져오거나 설정합니다.
기본값은 4입니다.


**Returns:**
double
### setBlur(double value) {#setBlur-double-}
```
public final void setBlur(double value)
```


그림자의 흐림 정도를 가져오거나 설정합니다.
기본값은 4입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

