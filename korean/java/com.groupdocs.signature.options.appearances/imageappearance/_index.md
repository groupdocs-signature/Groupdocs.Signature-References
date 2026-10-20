---
title: "ImageAppearance"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 서명의 확장된 외관 기능을 설명합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.appearances/imageappearance/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.appearances.SignatureAppearance](../../com.groupdocs.signature.options.appearances/signatureappearance)
```
public class ImageAppearance extends SignatureAppearance
```

이미지 서명의 확장된 외관 기능을 설명합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageAppearance()](#ImageAppearance--) | 기본값으로 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getGrayscale()](#getGrayscale--) | 그레이스케일 필터가 필요하면 이 플래그를 true로 설정합니다. |
|
|  | [setGrayscale(boolean value)](#setGrayscale-boolean-) | 그레이스케일 필터가 필요하면 이 플래그를 true로 설정합니다. |
|
|  | [getBrightness()](#getBrightness--) | 이미지 밝기를 가져오거나 설정합니다. |
|
|  | [setBrightness(float value)](#setBrightness-float-) | 이미지 밝기를 가져오거나 설정합니다. |
|
|  | [getContrast()](#getContrast--) | 이미지 대비를 가져오거나 설정합니다. |
|
|  | [setContrast(float value)](#setContrast-float-) | 이미지 대비를 가져오거나 설정합니다. |
|
|  | [getGammaCorrection()](#getGammaCorrection--) | 이미지 감마를 가져오거나 설정합니다. |
|
|  | [setGammaCorrection(float value)](#setGammaCorrection-float-) | 이미지 감마를 가져오거나 설정합니다. |
|
### ImageAppearance() {#ImageAppearance--}
```
public ImageAppearance()
```


기본값으로 인스턴스를 생성합니다.


### getGrayscale() {#getGrayscale--}
```
public final boolean getGrayscale()
```


그레이스케일 필터가 필요하면 이 플래그를 true로 설정합니다.


**Returns:**
boolean
### setGrayscale(boolean value) {#setGrayscale-boolean-}
```
public final void setGrayscale(boolean value)
```


그레이스케일 필터가 필요하면 이 플래그를 true로 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getBrightness() {#getBrightness--}
```
public final float getBrightness()
```


이미지 밝기를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 밝기에 해당합니다.


**Returns:**
float
### setBrightness(float value) {#setBrightness-float-}
```
public final void setBrightness(float value)
```


이미지 밝기를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 밝기에 해당합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### getContrast() {#getContrast--}
```
public final float getContrast()
```


이미지 대비를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 대비에 해당합니다.


**Returns:**
float
### setContrast(float value) {#setContrast-float-}
```
public final void setContrast(float value)
```


이미지 대비를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 대비에 해당합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

### getGammaCorrection() {#getGammaCorrection--}
```
public final float getGammaCorrection()
```


이미지 감마를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 감마에 해당합니다.


**Returns:**
float
### setGammaCorrection(float value) {#setGammaCorrection-float-}
```
public final void setGammaCorrection(float value)
```


이미지 감마를 가져오거나 설정합니다.
기본값은 1이며, 이는 이미지의 원래 감마에 해당합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float |  |

