---
title: "TextSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "텍스트 서명 옵션을 나타냅니다."
type: docs
weight: 18
url: /ko/java/com.groupdocs.signature.options.sign/textsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions)

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.interfaces.IRectangle](../../com.groupdocs.signature.domain.interfaces/irectangle), [com.groupdocs.signature.domain.interfaces.IAlignment](../../com.groupdocs.signature.domain.interfaces/ialignment), [com.groupdocs.signature.domain.interfaces.IRotation](../../com.groupdocs.signature.domain.interfaces/irotation), [com.groupdocs.signature.domain.interfaces.ITransparency](../../com.groupdocs.signature.domain.interfaces/itransparency)
```
public class TextSignOptions extends SignOptions implements IRectangle, IAlignment, IRotation, ITransparency
```

텍스트 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [TextSignOptions()](#TextSignOptions--) | SignTextOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [TextSignOptions(String text)](#TextSignOptions-java.lang.String-) | SignTextOptions 클래스의 새 인스턴스를 텍스트와 함께 초기화합니다. |
|
## 필드

| 필드 | 설명 |
| --- | --- |
| [DEFAULT_TRANSPARENCY](#DEFAULT-TRANSPARENCY) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getLeft()](#getLeft--) | 문서 페이지에서 서명의 왼쪽 X 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
|
|  | [setLeft(int value)](#setLeft-int-) | 문서 페이지에서 서명의 왼쪽 X 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
|
|  | [getTop()](#getTop--) | 문서 페이지에서 서명의 상단 Y 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
|
|  | [setTop(int value)](#setTop-int-) | 문서 페이지에서 서명의 상단 Y 위치 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
|
|  | [getWidth()](#getWidth--) | 문서 페이지에서 서명의 너비 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).
|
|  | [setWidth(int value)](#setWidth-int-) | 문서 페이지에서 서명의 너비 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).
|
|  | [getHeight()](#getHeight--) | 문서 페이지에서 서명의 높이 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).
|
|  | [setHeight(int value)](#setHeight-int-) | 문서 페이지에서 서명의 높이 (측정값) |
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).
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
|  | [getText()](#getText--) | 서명의 텍스트를 가져오거나 설정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | 서명의 텍스트를 가져오거나 설정합니다. |
|
|  | [getFont()](#getFont--) | 서명의 글꼴을 가져오거나 설정합니다. |
|
|  | [setFont(SignatureFont value)](#setFont-com.groupdocs.signature.domain.SignatureFont-) | 서명의 글꼴을 가져오거나 설정합니다. |
|
|  | [getFontOrDefault()](#getFontOrDefault--) | 내부: 이 인스턴스가 생성될 때 사용된 글꼴 또는 기본 글꼴입니다. |
|
|  | [getForeColor()](#getForeColor--) | 서명의 전경색을 가져오거나 설정합니다. |
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | 서명의 전경색을 가져오거나 설정합니다. |
|
|  | [getSignatureImplementation()](#getSignatureImplementation--) | 텍스트 서명 구현 유형을 가져오거나 설정합니다. |
|
|  | [setSignatureImplementation(int value)](#setSignatureImplementation-int-) | 텍스트 서명 구현 유형을 가져오거나 설정합니다. |
|
|  | [getTextHorizontalAlignment()](#getTextHorizontalAlignment--) | 서명 내부 텍스트의 가로 정렬. |
|
|  | [setTextHorizontalAlignment(int value)](#setTextHorizontalAlignment-int-) | 서명 내부 텍스트의 가로 정렬. |
|
|  | [getTextVerticalAlignment()](#getTextVerticalAlignment--) | 서명 내부 텍스트의 세로 정렬. |
|
|  | [setTextVerticalAlignment(int value)](#setTextVerticalAlignment-int-) | 서명 내부 텍스트의 세로 정렬. |
|
|  | [getFormTextFieldTitle()](#getFormTextFieldTitle--) | 텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다. |
|
|  | [setFormTextFieldTitle(String value)](#setFormTextFieldTitle-java.lang.String-) | 텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다. |
|
|  | [getFormTextFieldType()](#getFormTextFieldType--) | 텍스트 서명을 넣을 양식 필드 유형을 가져오거나 설정합니다. |
|
|  | [setFormTextFieldType(int value)](#setFormTextFieldType-int-) | 텍스트 서명을 넣을 양식 필드 유형을 가져오거나 설정합니다. |
|
|  | [getShapeType()](#getShapeType--) | 텍스트를 넣을 도형 유형을 가져오거나 설정합니다. |
|
|  | [setShapeType(int value)](#setShapeType-int-) | 텍스트를 넣을 도형 유형을 가져오거나 설정합니다. |
|
|  | [getSignatureID()](#getSignatureID--) | 서명의 고유 ID를 가져오거나 설정합니다. |
|
|  | [setSignatureID(int value)](#setSignatureID-int-) | 서명의 고유 ID를 가져오거나 설정합니다. |
|
|  | [getBorder()](#getBorder--) | 테두리 설정을 지정합니다. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 테두리 설정을 지정합니다. |
|
|  | [getBackground()](#getBackground--) | 서명 배경 설정을 가져오거나 설정합니다. |
|
|  | [setBackground(Background value)](#setBackground-com.groupdocs.signature.domain.Background-) | 서명 배경 설정을 가져오거나 설정합니다. |
|
|  | [getNative()](#getNative--) | 네이티브 속성을 가져오거나 설정합니다. |
|
|  | [setNative(boolean value)](#setNative-boolean-) | 네이티브 속성을 가져오거나 설정합니다. |
|
|  | [getShapePosition()](#getShapePosition--) | 문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다. |
|
|  | [setShapePosition(int value)](#setShapePosition-int-) | 문서 레이아웃에서 도형이 표시되어야 할 위치를 정의합니다. |
|
|  | [validate()](#validate--) | 옵션 매개변수를 검증하기 위한 내부 메서드입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### TextSignOptions() {#TextSignOptions--}
```
public TextSignOptions()
```


SignTextOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### TextSignOptions(String text) {#TextSignOptions-java.lang.String-}
```
public TextSignOptions(String text)
```


SignTextOptions 클래스의 새 인스턴스를 텍스트와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 서명 텍스트. |
|

### DEFAULT_TRANSPARENCY {#DEFAULT-TRANSPARENCY}
```
public static final double DEFAULT_TRANSPARENCY
```


### getLeft() {#getLeft--}
```
public final int getLeft()
```


문서 페이지에서 서명의 왼쪽 X 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
(수평 정렬이 지정되지 않은 경우 작동합니다.)


**Returns:**
int
### setLeft(int value) {#setLeft-int-}
```
public final void setLeft(int value)
```


문서 페이지에서 서명의 왼쪽 X 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
(수평 정렬이 지정되지 않은 경우 작동합니다.)


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTop() {#getTop--}
```
public final int getTop()
```


문서 페이지에서 서명의 상단 Y 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
(수직 정렬이 지정되지 않은 경우 작동합니다.)


**Returns:**
int
### setTop(int value) {#setTop-int-}
```
public final void setTop(int value)
```


문서 페이지에서 서명의 상단 Y 위치 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) LocationMeasureType 속성을 참조하십시오).
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
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


문서 페이지에서 서명의 너비 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


문서 페이지에서 서명의 높이 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


문서 페이지에서 서명의 높이 (측정값)
(픽셀, 퍼센트 또는 밀리미터, [MeasureType](../../com.groupdocs.signature.domain.enums/measuretype) SizeMeasureType 속성을 참조하십시오).


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

### getText() {#getText--}
```
public final String getText()
```


서명의 텍스트를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


서명의 텍스트를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFont() {#getFont--}
```
public final SignatureFont getFont()
```


서명의 글꼴을 가져오거나 설정합니다.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### setFont(SignatureFont value) {#setFont-com.groupdocs.signature.domain.SignatureFont-}
```
public final void setFont(SignatureFont value)
```


서명의 글꼴을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [SignatureFont](../../com.groupdocs.signature.domain/signaturefont) |  |

### getFontOrDefault() {#getFontOrDefault--}
```
public final SignatureFont getFontOrDefault()
```


내부: 이 인스턴스가 생성될 때 사용된 글꼴 또는 기본 글꼴입니다.


**Returns:**
[SignatureFont](../../com.groupdocs.signature.domain/signaturefont)
### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


서명의 전경색을 가져오거나 설정합니다.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


서명의 전경색을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### getSignatureImplementation() {#getSignatureImplementation--}
```
public final int getSignatureImplementation()
```


텍스트 서명 구현 유형을 가져오거나 설정합니다.


**Returns:**
int
### setSignatureImplementation(int value) {#setSignatureImplementation-int-}
```
public final void setSignatureImplementation(int value)
```


텍스트 서명 구현 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTextHorizontalAlignment() {#getTextHorizontalAlignment--}
```
public final int getTextHorizontalAlignment()
```


서명 내부 텍스트의 가로 정렬.
이 기능은 이미지 및 주석 서명 구현에만 지원됩니다
(참조 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 속성).


**Returns:**
int
### setTextHorizontalAlignment(int value) {#setTextHorizontalAlignment-int-}
```
public final void setTextHorizontalAlignment(int value)
```


서명 내부 텍스트의 가로 정렬.
이 기능은 이미지 및 주석 서명 구현에만 지원됩니다
(참조 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 속성).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTextVerticalAlignment() {#getTextVerticalAlignment--}
```
public final int getTextVerticalAlignment()
```


서명 내부 텍스트의 세로 정렬.
이 기능은 이미지 서명 구현에만 지원됩니다
(참조 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 속성).


**Returns:**
int
### setTextVerticalAlignment(int value) {#setTextVerticalAlignment-int-}
```
public final void setTextVerticalAlignment(int value)
```


서명 내부 텍스트의 세로 정렬.
이 기능은 이미지 서명 구현에만 지원됩니다
(참조 [TextSignatureImplementation](../../com.groupdocs.signature.domain.enums/textsignatureimplementation) SignatureImplementation 속성).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFormTextFieldTitle() {#getFormTextFieldTitle--}
```
public final String getFormTextFieldTitle()
```


텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다.


**Returns:**
java.lang.String
### setFormTextFieldTitle(String value) {#setFormTextFieldTitle-java.lang.String-}
```
public final void setFormTextFieldTitle(String value)
```


텍스트 서명을 넣을 텍스트 양식 필드의 제목을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getFormTextFieldType() {#getFormTextFieldType--}
```
public final int getFormTextFieldType()
```


텍스트 서명을 넣을 양식 필드 유형을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다.
값의 기본값은 AllTextTypes입니다.


**Returns:**
int
### setFormTextFieldType(int value) {#setFormTextFieldType-int-}
```
public final void setFormTextFieldType(int value)
```


텍스트 서명을 넣을 양식 필드 유형을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextToFormField인 경우에만 사용할 수 있습니다.
값의 기본값은 AllTextTypes입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getShapeType() {#getShapeType--}
```
public final int getShapeType()
```


텍스트를 넣을 도형 유형을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextStamp인 경우에만 사용할 수 있습니다.
값의 기본값은 Rectangle입니다.


**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public final void setShapeType(int value)
```


텍스트를 넣을 도형 유형을 가져오거나 설정합니다.
이 속성은 SignatureImplementation = TextStamp인 경우에만 사용할 수 있습니다.
값의 기본값은 Rectangle입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSignatureID() {#getSignatureID--}
```
public final int getSignatureID()
```


서명의 고유 ID를 가져오거나 설정합니다. 서명 검증 옵션에서 사용할 수 있습니다. 이 속성은 Pdf 문서에만 지원됩니다.


**Returns:**
int
### setSignatureID(int value) {#setSignatureID-int-}
```
public final void setSignatureID(int value)
```


서명의 고유 ID를 가져오거나 설정합니다. 서명 검증 옵션에서 사용할 수 있습니다. 이 속성은 Pdf 문서에만 지원됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

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

### getBackground() {#getBackground--}
```
public final Background getBackground()
```


서명 배경 설정을 가져오거나 설정합니다.


**Returns:**
[Background](../../com.groupdocs.signature.domain/background)
### setBackground(Background value) {#setBackground-com.groupdocs.signature.domain.Background-}
```
public final void setBackground(Background value)
```


서명 배경 설정을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Background](../../com.groupdocs.signature.domain/background) |  |

### getNative() {#getNative--}
```
public final boolean getNative()
```


네이티브 속성을 가져오거나 설정합니다. 설정하면 문서별 서명을 사용할 수 있습니다.
WordProcessing 문서에 대한 네이티브 텍스트 워터마크는 일반 워터마크와 다릅니다, 예를 들어.


**Returns:**
boolean
### setNative(boolean value) {#setNative-boolean-}
```
public final void setNative(boolean value)
```


네이티브 속성을 가져오거나 설정합니다. 설정하면 문서별 서명을 사용할 수 있습니다.
WordProcessing 문서에 대한 네이티브 텍스트 워터마크는 일반 워터마크와 다릅니다, 예를 들어.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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

### validate() {#validate--}
```
public void validate()
```


옵션 매개변수를 검증하기 위한 내부 메서드입니다.


### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
