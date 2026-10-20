---
title: "StampSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스탬프 서명 옵션을 나타냅니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.signature.options.sign/stampsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class StampSignOptions extends ImageSignOptions
```

스탬프 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [StampSignOptions()](#StampSignOptions--) | 기본값으로 StampSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [StampSignOptions(int left, int top, int width, int height)](#StampSignOptions-int-int-int-int-) | 정렬 옵션으로 StampSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getStampType()](#getStampType--) | 스탬프 유형을 가져오거나 설정합니다. |
|
|  | [setStampType(StampType value)](#setStampType-com.groupdocs.signature.domain.stamps.StampType-) | 스탬프 유형을 가져오거나 설정합니다. |
|
|  | [getOuterLines()](#getOuterLines--) | 동심원으로 렌더링되는 외부 선 목록입니다. |
|
|  | [getInnerLines()](#getInnerLines--) | 사각형 집합으로 렌더링되는 내부 선 목록입니다. |
|
|  | [getBackground()](#getBackground--) | 스탬프 배경을 가져오거나 설정합니다. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | 스탬프 배경을 가져오거나 설정합니다. |
|
|  | [getBackgroundColor()](#getBackgroundColor--) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [setBackgroundColor(Color value)](#setBackgroundColor-java.awt.Color-) | 서명의 배경 색상을 가져오거나 설정합니다. |
|
|  | [getBackgroundBrush()](#getBackgroundBrush--) | 서명 배경 브러시를 가져오거나 설정합니다. |
|
|  | [setBackgroundBrush(Brush value)](#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-) | 서명 배경 브러시를 가져오거나 설정합니다. |
|
|  | [getBackgroundColorCropType()](#getBackgroundColorCropType--) | 서명의 배경 색상 자르기 유형을 가져오거나 설정합니다. |
|
|  | [setBackgroundColorCropType(int value)](#setBackgroundColorCropType-int-) | 서명의 배경 색상 자르기 유형을 가져오거나 설정합니다. |
|
|  | [getBackgroundImageCropType()](#getBackgroundImageCropType--) | 서명의 배경 이미지 자르기 유형을 가져오거나 설정합니다. |
|
|  | [setBackgroundImageCropType(int value)](#setBackgroundImageCropType-int-) | 서명의 배경 이미지 자르기 유형을 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다 |
|
### StampSignOptions() {#StampSignOptions--}
```
public StampSignOptions()
```


기본값으로 StampSignOptions 클래스의 새 인스턴스를 초기화합니다.


### StampSignOptions(int left, int top, int width, int height) {#StampSignOptions-int-int-int-int-}
```
public StampSignOptions(int left, int top, int width, int height)
```


정렬 옵션으로 StampSignOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 왼쪽 | int | 스탬프 서명의 왼쪽 상단 모서리의 x 좌표 |
|
|  | 위 | int | 스탬프 서명의 왼쪽 상단 모서리의 y 좌표 |
|
|  | 너비 | int | Stamp Signature의 너비 |
|
|  | 높이 | int | Stamp Signature의 높이 |
|

### getStampType() {#getStampType--}
```
public final StampType getStampType()
```


스탬프 유형을 가져오거나 설정합니다.
기본값은 Round입니다.


**Returns:**
[StampType](../../com.groupdocs.signature.domain.stamps/stamptype)
### setStampType(StampType value) {#setStampType-com.groupdocs.signature.domain.stamps.StampType-}
```
public final void setStampType(StampType value)
```


스탬프 유형을 가져오거나 설정합니다.
기본값은 Round입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [StampType](../../com.groupdocs.signature.domain.stamps/stamptype) |  |

### getOuterLines() {#getOuterLines--}
```
public final List<StampLine> getOuterLines()
```


동심원으로 렌더링되는 외부 선 목록입니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getInnerLines() {#getInnerLines--}
```
public final List<StampLine> getInnerLines()
```


사각형 집합으로 렌더링되는 내부 선 목록입니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.stamps.StampLine>
### getBackground() {#getBackground--}
```
public final Background getBackground()
```


스탬프 배경을 가져오거나 설정합니다.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


스탬프 배경을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

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

### getBackgroundBrush() {#getBackgroundBrush--}
```
public final Brush getBackgroundBrush()
```


서명 배경 브러시를 가져오거나 설정합니다. 기본값은 null입니다.


**Returns:**
[Brush](../../com.groupdocs.signature.domain.extensions/brush)
### setBackgroundBrush(Brush value) {#setBackgroundBrush-com.groupdocs.signature.domain.extensions.Brush-}
```
public final void setBackgroundBrush(Brush value)
```


서명 배경 브러시를 가져오거나 설정합니다. 기본값은 null입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Brush](../../com.groupdocs.signature.domain.extensions/brush) |  |

### getBackgroundColorCropType() {#getBackgroundColorCropType--}
```
public final int getBackgroundColorCropType()
```


서명의 배경 색상 자르기 유형을 가져오거나 설정합니다.


**Returns:**
int
### setBackgroundColorCropType(int value) {#setBackgroundColorCropType-int-}
```
public final void setBackgroundColorCropType(int value)
```


서명의 배경 색상 자르기 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getBackgroundImageCropType() {#getBackgroundImageCropType--}
```
public final int getBackgroundImageCropType()
```


서명의 배경 이미지 자르기 유형을 가져오거나 설정합니다.


**Returns:**
int
### setBackgroundImageCropType(int value) {#setBackgroundImageCropType-int-}
```
public final void setBackgroundImageCropType(int value)
```


서명의 배경 이미지 자르기 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다


**Returns:**
java.lang.String -
