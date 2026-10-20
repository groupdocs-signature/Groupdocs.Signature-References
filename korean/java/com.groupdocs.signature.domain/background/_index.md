---
title: "Background"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "배경 모양을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain/background/
---
**Inheritance:**
java.lang.Object
```
public class Background
```

배경 모양을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Background()](#Background--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getColor()](#getColor--) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 배경 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 배경 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지). |
|
|  | [getBrush()](#getBrush--) | 배경 브러시를 가져오거나 설정합니다. |
|
|  | [setBrush(Brush value)](#setBrush-com.groupdocs.signature.domain.extensions.Brush-) | 배경 브러시를 가져오거나 설정합니다. |
|
### Background() {#Background--}
```
public Background()
```


### getColor() {#getColor--}
```
public final Color getColor()
```


서명의 배경 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


서명의 배경 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


서명의 배경 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


배경 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


배경 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getBrush() {#getBrush--}
```
public final Brush getBrush()
```


배경 브러시를 가져오거나 설정합니다. 기본값은 null입니다.
이 속성은 Brush 객체 구현 인스턴스를 기대합니다.
다양한 Brush 클래스를 참조하세요.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBrush(Brush value) {#setBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBrush(Brush value)
```


배경 브러시를 가져오거나 설정합니다. 기본값은 null입니다.
이 속성은 Brush 객체 구현 인스턴스를 기대합니다.
다양한 Brush 클래스를 참조하세요.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

