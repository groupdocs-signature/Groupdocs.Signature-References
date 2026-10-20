---
title: "LinearGradientBrush"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "선형 그라디언트 브러시를 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.extensions/lineargradientbrush/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.Brush](../../com.groupdocs.signature.domain.extensions/brush)
```
public class LinearGradientBrush extends Brush
```

선형 그라디언트 브러시를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [LinearGradientBrush()](#LinearGradientBrush--) | LinearGradientBrush 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [LinearGradientBrush(Color startColor, Color endColor, float angle)](#LinearGradientBrush-java.awt.Color-java.awt.Color-float-) | LinearGradientBrush 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LinearGradientBrush(String startColor, String endColor, float angle)](#LinearGradientBrush-java.lang.String-java.lang.String-float-) | LinearGradientBrush 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStartColor()](#getStartColor--) | 시작 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [setStartColor(Color value)](#setStartColor-java.awt.Color-) | 시작 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [setStartColor(String value)](#setStartColor-java.lang.String-) | 시작 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [getEndColor()](#getEndColor--) | 끝 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [setEndColor(Color value)](#setEndColor-java.awt.Color-) | 끝 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [setEndColor(String value)](#setEndColor-java.lang.String-) | 끝 그라디언트 색상을 가져오거나 설정합니다. |
|
|  | [getAngle()](#getAngle--) | 그라디언트 각도를 가져오거나 설정합니다. |
|
|  | [setAngle(float value)](#setAngle-float-) | 그라디언트 각도를 가져오거나 설정합니다. |
|
### LinearGradientBrush() {#LinearGradientBrush--}
```
public LinearGradientBrush()
```


LinearGradientBrush 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### LinearGradientBrush(Color startColor, Color endColor, float angle) {#LinearGradientBrush-java.awt.Color-java.awt.Color-float-}
```
public LinearGradientBrush(Color startColor, Color endColor, float angle)
```


LinearGradientBrush 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | startColor | java.awt.Color | 시작 색상. |
|
|  | endColor | java.awt.Color | 끝 색상. |
|
|  | 각도 | float | 각도. 기본값은 0입니다. |
|

### LinearGradientBrush(String startColor, String endColor, float angle) {#LinearGradientBrush-java.lang.String-java.lang.String-float-}
```
public LinearGradientBrush(String startColor, String endColor, float angle)
```


LinearGradientBrush 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | startColor | java.lang.String | 시작 색상. |
|
|  | endColor | java.lang.String | 끝 색상. |
|
|  | 각도 | float | 각도. 기본값은 0입니다. |
|

### getStartColor() {#getStartColor--}
```
public final Color getStartColor()
```


시작 그라디언트 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setStartColor(Color value) {#setStartColor-java.awt.Color-}
```
public final void setStartColor(Color value)
```


시작 그라디언트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setStartColor(String value) {#setStartColor-java.lang.String-}
```
public final void setStartColor(String value)
```


시작 그라디언트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getEndColor() {#getEndColor--}
```
public final Color getEndColor()
```


끝 그라디언트 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setEndColor(Color value) {#setEndColor-java.awt.Color-}
```
public final void setEndColor(Color value)
```


끝 그라디언트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setEndColor(String value) {#setEndColor-java.lang.String-}
```
public final void setEndColor(String value)
```


끝 그라디언트 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getAngle() {#getAngle--}
```
public final float getAngle()
```


그라디언트 각도를 가져오거나 설정합니다.


**Returns:**
float
### setAngle(float value) {#setAngle-float-}
```
public final void setAngle(float value)
```


그라디언트 각도를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

