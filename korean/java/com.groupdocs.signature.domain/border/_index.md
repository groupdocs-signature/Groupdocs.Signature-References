---
title: "테두리"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "테두리 선 속성을 보관하는 인스턴스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain/border/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class Border implements ITransparency
```

테두리 선 속성을 보관하는 인스턴스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Border()](#Border--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getDashStyle()](#getDashStyle--) | 서명 테두리 스타일을 가져오거나 설정합니다. |
|
|  | [setDashStyle(int value)](#setDashStyle-int-) | 서명 테두리 스타일을 가져오거나 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 서명 테두리 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지). |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 서명 테두리 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지). |
|
|  | [getWeight()](#getWeight--) | 서명 테두리의 두께를 가져오거나 설정합니다. |
|
|  | [setWeight(double value)](#setWeight-double-) | 서명 테두리의 두께를 가져오거나 설정합니다. |
|
|  | [getColor()](#getColor--) | 서명의 테두리 색상을 가져오거나 설정합니다. |
|
|  | [setColor(Color value)](#setColor-java.awt.Color-) | 서명의 테두리 색상을 가져오거나 설정합니다. |
|
|  | [setColor(String value)](#setColor-java.lang.String-) | 서명의 테두리 색상을 가져오거나 설정합니다. |
|
|  | [getVisible()](#getVisible--) | 테두리 표시 여부를 가져오거나 설정합니다. |
|
| [setVisible(boolean value)](#setVisible-boolean-) |  |
|  | [deepClone()](#deepClone--) | IClonable 인터페이스를 구현합니다 |
|
### Border() {#Border--}
```
public Border()
```


### getDashStyle() {#getDashStyle--}
```
public final int getDashStyle()
```


서명 테두리 스타일을 가져오거나 설정합니다.


**Returns:**
int
### setDashStyle(int value) {#setDashStyle-int-}
```
public final void setDashStyle(int value)
```


서명 테두리 스타일을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


서명 테두리 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지).


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


서명 테두리 투명도를 가져오거나 설정합니다 (값은 0.0(불투명)부터 1.0(투명)까지).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getWeight() {#getWeight--}
```
public final double getWeight()
```


서명 테두리의 두께를 가져오거나 설정합니다.


**Returns:**
double
### setWeight(double value) {#setWeight-double-}
```
public final void setWeight(double value)
```


서명 테두리의 두께를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getColor() {#getColor--}
```
public final Color getColor()
```


서명의 테두리 색상을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


서명의 테두리 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setColor(String value) {#setColor-java.lang.String-}
```
public final void setColor(String value)
```


서명의 테두리 색상을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getVisible() {#getVisible--}
```
public boolean getVisible()
```


테두리 표시 여부를 가져오거나 설정합니다.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


IClonable 인터페이스를 구현합니다


**Returns:**
java.lang.Object - 동일한 속성을 가진 새로 만든 Border 인스턴스

