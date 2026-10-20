---
title: "SquareBorder"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "정사각형 스탬프 라인의 테두리 선 속성을 유지하기 위한 인스턴스입니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.stamps/squareborder/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.Border](../../com.groupdocs.signature.domain/border)
```
public class SquareBorder extends Border
```

정사각형 스탬프 라인의 테두리 선 속성을 유지하기 위한 인스턴스입니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SquareBorder(double radius)](#SquareBorder-double-) | SquareBorderLine을 둥근 모서리 반경으로 생성합니다. |
|
|  | [SquareBorder(Corners corners)](#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-) | SquareBorderLine을 모서리 반경 값으로 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getRadius()](#getRadius--) | 정사각형 모서리의 반경을 가져오거나 설정합니다. |
|
|  | [setRadius(Corners value)](#setRadius-com.groupdocs.signature.domain.stamps.Corners-) | 정사각형 모서리의 반경을 가져오거나 설정합니다. |
|
### SquareBorder(double radius) {#SquareBorder-double-}
```
public SquareBorder(double radius)
```


SquareBorderLine을 둥근 모서리 반경으로 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | radius | double | 정사각형 모서리의 반경. |
|

### SquareBorder(Corners corners) {#SquareBorder-com.groupdocs.signature.domain.stamps.Corners-}
```
public SquareBorder(Corners corners)
```


SquareBorderLine을 모서리 반경 값으로 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | corners | [Corners](../../com.groupdocs.signature.domain.stamps/corners) | 정사각형 모서리의 반경. |
|

### getRadius() {#getRadius--}
```
public final Corners getRadius()
```


정사각형 모서리의 반경을 가져오거나 설정합니다.


**Returns:**
[Corners](../../com.groupdocs.signature.domain.stamps/corners)
### setRadius(Corners value) {#setRadius-com.groupdocs.signature.domain.stamps.Corners-}
```
public final void setRadius(Corners value)
```


정사각형 모서리의 반경을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Corners](../../com.groupdocs.signature.domain.stamps/corners) |  |

