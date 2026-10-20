---
title: "ImageSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 서명 옵션을 나타냅니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.sign/imagesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency), com.aspose.ms.System.IDisposable
```
public class ImageSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency, System.IDisposable
```

이미지 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageSignOptions()](#ImageSignOptions--) | ImageSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [ImageSignOptions(String imageFilePath)](#ImageSignOptions-java.lang.String-) | ImageSignOptions 클래스의 새 인스턴스를 이미지 파일로 초기화합니다. |
|
|  | [ImageSignOptions(InputStream imageStream)](#ImageSignOptions-java.io.InputStream-) | ImageSignOptions 클래스의 새 인스턴스를 이미지 스트림으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getImageFilePath()](#getImageFilePath--) | 서명 이미지 파일 경로를 가져오거나 설정합니다. |
|
|  | [setImageFilePath(String value)](#setImageFilePath-java.lang.String-) | 서명 이미지 파일 경로를 가져오거나 설정합니다. |
|
|  | [getImageStream()](#getImageStream--) | 서명 이미지 스트림을 가져오거나 설정합니다. |
|
|  | [setImageStream(InputStream value)](#setImageStream-java.io.InputStream-) | 서명 이미지 스트림을 가져오거나 설정합니다. |
|
|  | [getLeft()](#getLeft--) | 문서 페이지에서 서명의 왼쪽 X 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
|
|  | [setLeft(int value)](#setLeft-int-) | 문서 페이지에서 서명의 왼쪽 X 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
|
|  | [getTop()](#getTop--) | 문서 페이지에서 서명의 상단 Y 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
|
|  | [setTop(int value)](#setTop-int-) | 문서 페이지에서 서명의 상단 Y 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
|
|  | [getWidth()](#getWidth--) | 문서 페이지에서 서명의 너비 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [setWidth(int value)](#setWidth-int-) | 문서 페이지에서 서명의 너비 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).
|
|  | [getHeight()](#getHeight--) | 문서 페이지에서 서명의 높이 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType을 참조).
|
|  | [setHeight(int value)](#setHeight-int-) | 문서 페이지에서 서명의 높이 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType을 참조).
|
|  | [getLocationMeasureType()](#getLocationMeasureType--) | 왼쪽 및 위쪽 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터). |
|
|  | [setLocationMeasureType(int value)](#setLocationMeasureType-int-) | 왼쪽 및 위쪽 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터). |
|
|  | [getSizeMeasureType()](#getSizeMeasureType--) | 너비 및 높이 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터). |
|
|  | [setSizeMeasureType(int value)](#setSizeMeasureType-int-) | 너비 및 높이 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터). |
|
|  | [getStretch()](#getStretch--) | 문서 페이지의 스트레치 모드. |
|
|  | [setStretch(int value)](#setStretch-int-) | 문서 페이지의 스트레치 모드. |
|
|  | [getRotationAngle()](#getRotationAngle--) | 문서 페이지에서 서명의 회전 각도 (시계 방향). |
|
|  | [setRotationAngle(int value)](#setRotationAngle-int-) | 문서 페이지에서 서명의 회전 각도 (시계 방향). |
|
|  | [getHorizontalAlignment()](#getHorizontalAlignment--) | 문서 페이지에서 서명의 수평 정렬. |
|
|  | [setHorizontalAlignment(int value)](#setHorizontalAlignment-int-) | 문서 페이지에서 서명의 수평 정렬. |
|
|  | [getVerticalAlignment()](#getVerticalAlignment--) | 문서 페이지에서 서명의 수직 정렬. |
|
|  | [setVerticalAlignment(int value)](#setVerticalAlignment-int-) | 문서 페이지에서 서명의 수직 정렬. |
|
|  | [getMargin()](#getMargin--) | 서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다. |
|
|  | [setMargin(Padding value)](#setMargin-com.groupdocs.signature.domain.Padding-) | 서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다. |
|
|  | [getMarginMeasureType()](#getMarginMeasureType--) | Margin에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
|
|  | [setMarginMeasureType(int value)](#setMarginMeasureType-int-) | Margin에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다. |
|
|  | [getTransparency()](#getTransparency--) | 서명의 투명도(0.0(불투명)에서 1.0(투명)까지 값)를 가져오거나 설정합니다. |
|
|  | [setTransparency(double value)](#setTransparency-double-) | 서명의 투명도(0.0(불투명)에서 1.0(투명)까지 값)를 가져오거나 설정합니다. |
|
|  | [getShapePosition()](#getShapePosition--) | 문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | 문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다. |
|
|  | [getRectangle()](#getRectangle--) | 문서에 이미지를 배치할 영역의 사각형입니다. |
|
|  | [getBorder()](#getBorder--) | 테두리 설정을 지정합니다. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 테두리 설정을 지정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
|  | [fromBase64(String base64Content)](#fromBase64-java.lang.String-) | Base64에서 미리 정의된 이미지를 사용하여 ImageSignOptions 클래스의 새 인스턴스를 생성합니다. |
|
|  | [dispose()](#dispose--) | 내부 리소스를 정리합니다. |
|
### ImageSignOptions() {#ImageSignOptions--}
```
public ImageSignOptions()
```


ImageSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### ImageSignOptions(String imageFilePath) {#ImageSignOptions-java.lang.String-}
```
public ImageSignOptions(String imageFilePath)
```


ImageSignOptions 클래스의 새 인스턴스를 이미지 파일로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | imageFilePath | java.lang.String | 이미지 파일 경로 |
|

### ImageSignOptions(InputStream imageStream) {#ImageSignOptions-java.io.InputStream-}
```
public ImageSignOptions(InputStream imageStream)
```


ImageSignOptions 클래스의 새 인스턴스를 이미지 스트림으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | imageStream | java.io.InputStream | 이미지 스트림 |
|

### getImageFilePath() {#getImageFilePath--}
```
public final String getImageFilePath()
```


서명 이미지 파일 경로를 가져오거나 설정합니다.
이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다.


**Returns:**
java.lang.String
### setImageFilePath(String value) {#setImageFilePath-java.lang.String-}
```
public final void setImageFilePath(String value)
```


서명 이미지 파일 경로를 가져오거나 설정합니다.
이 속성은 ImageStream이 지정되지 않은 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getImageStream() {#getImageStream--}
```
public final InputStream getImageStream()
```


서명 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 ImageGuid 대신 사용됩니다.


**Returns:**
java.io.InputStream
### setImageStream(InputStream value) {#setImageStream-java.io.InputStream-}
```
public final void setImageStream(InputStream value)
```


서명 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 ImageGuid 대신 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

### getLeft() {#getLeft--}
```
public int getLeft()
```


문서 페이지에서 서명의 왼쪽 X 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
(수평 정렬이 지정되지 않은 경우 작동합니다.)


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


문서 페이지에서 서명의 왼쪽 X 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
(수평 정렬이 지정되지 않은 경우 작동합니다.)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public int getTop()
```


문서 페이지에서 서명의 상단 Y 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
(수직 정렬이 지정되지 않은 경우 작동합니다.)


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


문서 페이지에서 서명의 상단 Y 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType을 참조).
(수직 정렬이 지정되지 않은 경우 작동합니다.)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getWidth() {#getWidth--}
```
public final int getWidth()
```


문서 페이지에서 서명의 너비 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


문서 페이지에서 서명의 너비 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


문서 페이지에서 서명의 높이 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType을 참조).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


문서 페이지에서 서명의 높이 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType을 참조).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLocationMeasureType() {#getLocationMeasureType--}
```
public int getLocationMeasureType()
```


왼쪽 및 위쪽 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터).


**Returns:**
int
### setLocationMeasureType(int value) {#setLocationMeasureType-int-}
```
public void setLocationMeasureType(int value)
```


왼쪽 및 위쪽 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSizeMeasureType() {#getSizeMeasureType--}
```
public int getSizeMeasureType()
```


너비 및 높이 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터).


**Returns:**
int
### setSizeMeasureType(int value) {#setSizeMeasureType-int-}
```
public void setSizeMeasureType(int value)
```


너비 및 높이 속성에 대한 측정 유형 (픽셀, 퍼센트 또는 밀리미터).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getStretch() {#getStretch--}
```
public final int getStretch()
```


문서 페이지의 스트레치 모드.


**Returns:**
int
### setStretch(int value) {#setStretch-int-}
```
public final void setStretch(int value)
```


문서 페이지의 스트레치 모드.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getRotationAngle() {#getRotationAngle--}
```
public final int getRotationAngle()
```


문서 페이지에서 서명의 회전 각도 (시계 방향).


**Returns:**
int
### setRotationAngle(int value) {#setRotationAngle-int-}
```
public final void setRotationAngle(int value)
```


문서 페이지에서 서명의 회전 각도 (시계 방향).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHorizontalAlignment() {#getHorizontalAlignment--}
```
public final int getHorizontalAlignment()
```


문서 페이지에서 서명의 수평 정렬.


**Returns:**
int
### setHorizontalAlignment(int value) {#setHorizontalAlignment-int-}
```
public final void setHorizontalAlignment(int value)
```


문서 페이지에서 서명의 수평 정렬.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getVerticalAlignment() {#getVerticalAlignment--}
```
public final int getVerticalAlignment()
```


문서 페이지에서 서명의 수직 정렬.


**Returns:**
int
### setVerticalAlignment(int value) {#setVerticalAlignment-int-}
```
public final void setVerticalAlignment(int value)
```


문서 페이지에서 서명의 수직 정렬.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getMargin() {#getMargin--}
```
public Padding getMargin()
```


서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다.
(수평 또는 수직 정렬이 지정된 경우에만 작동합니다.)


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setMargin(Padding value) {#setMargin-com.groupdocs.signature.domain.Padding-}
```
public void setMargin(Padding value)
```


서명과 문서 가장자리 사이의 간격을 가져오거나 설정합니다.
(수평 또는 수직 정렬이 지정된 경우에만 작동합니다.)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getMarginMeasureType() {#getMarginMeasureType--}
```
public int getMarginMeasureType()
```


Margin에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다.


**Returns:**
int
### setMarginMeasureType(int value) {#setMarginMeasureType-int-}
```
public void setMarginMeasureType(int value)
```


Margin에 대한 측정 유형(픽셀, 퍼센트 또는 밀리미터)을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTransparency() {#getTransparency--}
```
public final double getTransparency()
```


서명의 투명도(0.0(불투명)에서 1.0(투명)까지 값)를 가져오거나 설정합니다. 기본값은 0(불투명)입니다.


**Returns:**
double
### setTransparency(double value) {#setTransparency-double-}
```
public final void setTransparency(double value)
```


서명의 투명도(0.0(불투명)에서 1.0(투명)까지 값)를 가져오거나 설정합니다. 기본값은 0(불투명)입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getShapePosition() {#getShapePosition--}
```
public final int getShapePosition()
```


문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다.


**Returns:**
int
### setShapePosition(int value) {#setShapePosition-int-}
```
public final void setShapePosition(int value)
```


문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getRectangle() {#getRectangle--}
```
public final Rectangle getRectangle()
```


문서에 이미지를 배치할 영역의 사각형입니다.


**Returns:**
java.awt.Rectangle
### getBorder() {#getBorder--}
```
public final Border getBorder()
```


테두리 설정을 지정합니다.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


테두리 설정을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
### fromBase64(String base64Content) {#fromBase64-java.lang.String-}
```
public static ImageSignOptions fromBase64(String base64Content)
```


Base64에서 미리 정의된 이미지를 사용하여 ImageSignOptions 클래스의 새 인스턴스를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | base64Content | java.lang.String | Base64 문자열 형식의 이미지 콘텐츠 |
|

**Returns:**
[ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions) - 
### dispose() {#dispose--}
```
public final void dispose()
```


내부 리소스를 정리합니다.


