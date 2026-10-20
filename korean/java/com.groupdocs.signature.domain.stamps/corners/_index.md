---
title: "코너"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "정사각형 그래픽 객체의 모서리를 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.stamps/corners/
---
**Inheritance:**
java.lang.Object
```
public class Corners
```

정사각형 그래픽 객체의 모서리를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Corners()](#Corners--) | 0값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Corners(double all)](#Corners-double-) | 모든 모서리에 제공된 값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)](#Corners-double-double-double-double-) | 제공된 값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Empty](#Empty) | 데이터가 없는 Corners 객체를 제공합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 모서리의 값을 가져오거나 설정합니다. |
|
|  | [setAll(double value)](#setAll-double-) | 모든 모서리의 값을 가져오거나 설정합니다. |
|
|  | [getTopLeft()](#getTopLeft--) | 왼쪽 위 모서리 값을 가져오거나 설정합니다. |
|
|  | [setTopLeft(double value)](#setTopLeft-double-) | 왼쪽 위 모서리 값을 가져오거나 설정합니다. |
|
|  | [getTopRight()](#getTopRight--) | 오른쪽 위 모서리 값을 가져오거나 설정합니다. |
|
|  | [setTopRight(double value)](#setTopRight-double-) | 오른쪽 위 모서리 값을 가져오거나 설정합니다. |
|
|  | [getBottomLeft()](#getBottomLeft--) | 왼쪽 아래 모서리 값을 가져오거나 설정합니다. |
|
|  | [setBottomLeft(double value)](#setBottomLeft-double-) | 왼쪽 아래 모서리 값을 가져오거나 설정합니다. |
|
|  | [getBottomRight()](#getBottomRight--) | 오른쪽 아래 모서리 값을 가져오거나 설정합니다. |
|
|  | [setBottomRight(double value)](#setBottomRight-double-) | 오른쪽 아래 모서리 값을 가져오거나 설정합니다. |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | Equals 메서드를 재정의합니다 |
|
|  | [hashCode()](#hashCode--) | 고유 해시 코드 값을 가져오는 것을 재정의합니다 |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### Corners() {#Corners--}
```
public Corners()
```


0값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다.


### Corners(double all) {#Corners-double-}
```
public Corners(double all)
```


모든 모서리에 제공된 값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 전체 | double | 모든 모서리의 패딩에 사용할 값입니다. |
|

### Corners(double topLeft, double topRight, double bottomLeft, double bottomRight) {#Corners-double-double-double-double-}
```
public Corners(double topLeft, double topRight, double bottomLeft, double bottomRight)
```


제공된 값을 사용하여 Corners 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | topLeft | double | 왼쪽 위 모서리 값. |
|
|  | topRight | double | 오른쪽 위 모서리 값. |
|
|  | bottomLeft | double | 왼쪽 아래 모서리 값. |
|
|  | bottomRight | double | 오른쪽 아래 모서리 값. |
|

### Empty {#Empty}
```
public static final Corners Empty
```


데이터가 없는 Corners 객체를 제공합니다.


### getAll() {#getAll--}
```
public final double getAll()
```


모든 모서리의 값을 가져오거나 설정합니다.
top right와 같은 부분 모서리를 변경하면 이 속성이 0이 됩니다;


**Returns:**
double
### setAll(double value) {#setAll-double-}
```
public final void setAll(double value)
```


모든 모서리의 값을 가져오거나 설정합니다.
top right와 같은 부분 모서리를 변경하면 이 속성이 0이 됩니다;


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getTopLeft() {#getTopLeft--}
```
public final double getTopLeft()
```


왼쪽 위 모서리 값을 가져오거나 설정합니다.


**Returns:**
double
### setTopLeft(double value) {#setTopLeft-double-}
```
public final void setTopLeft(double value)
```


왼쪽 위 모서리 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getTopRight() {#getTopRight--}
```
public final double getTopRight()
```


오른쪽 위 모서리 값을 가져오거나 설정합니다.


**Returns:**
double
### setTopRight(double value) {#setTopRight-double-}
```
public final void setTopRight(double value)
```


오른쪽 위 모서리 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getBottomLeft() {#getBottomLeft--}
```
public final double getBottomLeft()
```


왼쪽 아래 모서리 값을 가져오거나 설정합니다.


**Returns:**
double
### setBottomLeft(double value) {#setBottomLeft-double-}
```
public final void setBottomLeft(double value)
```


왼쪽 아래 모서리 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getBottomRight() {#getBottomRight--}
```
public final double getBottomRight()
```


오른쪽 아래 모서리 값을 가져오거나 설정합니다.


**Returns:**
double
### setBottomRight(double value) {#setBottomRight-double-}
```
public final void setBottomRight(double value)
```


오른쪽 아래 모서리 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 객체의 복사본을 가져옵니다.


**Returns:**
java.lang.Object
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Equals 메서드를 재정의합니다


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 객체 | java.lang.Object | 비교할 인스턴스입니다. |
|

**Returns:**
boolean - 객체의 속성이 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


고유 해시 코드 값을 가져오는 것을 재정의합니다


**Returns:**
int -
### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
