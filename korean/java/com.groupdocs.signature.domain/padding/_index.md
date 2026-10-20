---
title: "패딩"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "요소와 관련된 패딩 또는 여백 정보를 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.domain/padding/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Cloneable
```
public class Padding implements Cloneable
```

요소와 관련된 패딩 또는 여백 정보를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [Padding()](#Padding--) | 제로 값을 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Padding(int all)](#Padding-int-) | 모든 가장자리에 제공된 패딩 크기를 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [Padding(int left, int right, int top, int bottom)](#Padding-int-int-int-int-) | 제공된 패딩 크기를 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
|  | [Empty](#Empty) | 패딩이 없는 Padding 객체를 제공합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAll()](#getAll--) | 모든 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [setAll(int value)](#setAll-int-) | 모든 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [getLeft()](#getLeft--) | 왼쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [setLeft(int value)](#setLeft-int-) | 왼쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [getRight()](#getRight--) | 오른쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [setRight(int value)](#setRight-int-) | 오른쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [getTop()](#getTop--) | 위쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [setTop(int value)](#setTop-int-) | 위쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [getBottom()](#getBottom--) | 아래쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [setBottom(int value)](#setBottom-int-) | 아래쪽 가장자리의 패딩 값을 가져오거나 설정합니다. |
|
|  | [getHorizontal()](#getHorizontal--) | 오른쪽 및 왼쪽 가장자리의 결합된 패딩을 가져옵니다. |
|
|  | [getVertical()](#getVertical--) | 위쪽 및 아래쪽 가장자리의 결합된 패딩을 가져옵니다. |
|
|  | [deepClone()](#deepClone--) | 이 객체의 복사본을 가져옵니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다 |
|
### Padding() {#Padding--}
```
public Padding()
```


제로 값을 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다.


### Padding(int all) {#Padding-int-}
```
public Padding(int all)
```


모든 가장자리에 제공된 패딩 크기를 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 전체 | int | 모든 가장자리에 사용할 패딩 측정 단위 수입니다. |
|

### Padding(int left, int right, int top, int bottom) {#Padding-int-int-int-int-}
```
public Padding(int left, int right, int top, int bottom)
```


제공된 패딩 크기를 사용하여 Padding 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 왼쪽 | int | 왼쪽 패딩 크기입니다. |
|
|  | 오른쪽 | int | 오른쪽 패딩 크기입니다. |
|
|  | 위 | int | 위쪽 패딩 크기입니다. |
|
|  | 아래쪽 | int | 아래쪽 패딩 크기입니다. |
|

### Empty {#Empty}
```
public static final Padding Empty
```


패딩이 없는 Padding 객체를 제공합니다.


### getAll() {#getAll--}
```
public final int getAll()
```


모든 가장자리의 패딩 값을 가져오거나 설정합니다.
왼쪽이나 위쪽과 같은 부분 가장자리를 변경하면 이 속성이 0이 됩니다;


**Returns:**
int
### setAll(int value) {#setAll-int-}
```
public final void setAll(int value)
```


모든 가장자리의 패딩 값을 가져오거나 설정합니다.
왼쪽이나 위쪽과 같은 부분 가장자리를 변경하면 이 속성이 0이 됩니다;


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLeft() {#getLeft--}
```
public final int getLeft()
```


왼쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


왼쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getRight() {#getRight--}
```
public final int getRight()
```


오른쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Returns:**
int
### setRight(int value) {#setRight-int-}
```
public final void setRight(int value)
```


오른쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


위쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


위쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getBottom() {#getBottom--}
```
public final int getBottom()
```


아래쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Returns:**
int
### setBottom(int value) {#setBottom-int-}
```
public final void setBottom(int value)
```


아래쪽 가장자리의 패딩 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHorizontal() {#getHorizontal--}
```
public final int getHorizontal()
```


오른쪽 및 왼쪽 가장자리의 결합된 패딩을 가져옵니다.


**Returns:**
int
### getVertical() {#getVertical--}
```
public final int getVertical()
```


위쪽 및 아래쪽 가장자리의 결합된 패딩을 가져옵니다.


**Returns:**
int
### deepClone() {#deepClone--}
```
public final Object deepClone()
```


이 객체의 복사본을 가져옵니다.


**Returns:**
java.lang.Object
### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다


**Returns:**
java.lang.String -
