---
title: "BmpSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 문서에 대한 BMP 저장 옵션."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/bmpsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public final class BmpSaveOptions extends ImageSaveOptions
```

이미지 문서에 대한 BMP 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [BmpSaveOptions()](#BmpSaveOptions--) | 기본값으로 BmpSaveOptions를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBitsPerPixel()](#getBitsPerPixel--) | 이미지 픽셀당 비트 수를 가져오거나 설정합니다. |
|
|  | [setBitsPerPixel(int value)](#setBitsPerPixel-int-) | 이미지 픽셀당 비트 수를 가져오거나 설정합니다. |
|
|  | [getCompression()](#getCompression--) | 압축을 가져오거나 설정합니다. |
|
|  | [setCompression(int value)](#setCompression-int-) | 압축을 가져오거나 설정합니다. |
|
|  | [getHorizontalResolution()](#getHorizontalResolution--) | 수평 해상도를 가져오거나 설정합니다. |
|
|  | [setHorizontalResolution(double value)](#setHorizontalResolution-double-) | 수평 해상도를 가져오거나 설정합니다. |
|
|  | [getVerticalResolution()](#getVerticalResolution--) | 수직 해상도를 가져오거나 설정합니다. |
|
|  | [setVerticalResolution(double value)](#setVerticalResolution-double-) | 수직 해상도를 가져오거나 설정합니다. |
|
### BmpSaveOptions() {#BmpSaveOptions--}
```
public BmpSaveOptions()
```


기본값으로 BmpSaveOptions를 생성합니다.


### getBitsPerPixel() {#getBitsPerPixel--}
```
public final int getBitsPerPixel()
```


이미지 픽셀당 비트 수를 가져오거나 설정합니다.


**Returns:**
int
### setBitsPerPixel(int value) {#setBitsPerPixel-int-}
```
public final void setBitsPerPixel(int value)
```


이미지 픽셀당 비트 수를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getCompression() {#getCompression--}
```
public final int getCompression()
```


압축을 가져오거나 설정합니다. 자세한 내용은 [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)을 참조하세요.


**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public final void setCompression(int value)
```


압축을 가져오거나 설정합니다. 자세한 내용은 [BitmapCompression](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/bitmapcompression)을 참조하세요.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHorizontalResolution() {#getHorizontalResolution--}
```
public final double getHorizontalResolution()
```


수평 해상도를 가져오거나 설정합니다. 참고: 반올림으로 인해 결과가
해상도가 전달된 값과 약간 다를 수 있습니다.


**Returns:**
double
### setHorizontalResolution(double value) {#setHorizontalResolution-double-}
```
public final void setHorizontalResolution(double value)
```


수평 해상도를 가져오거나 설정합니다. 참고: 반올림으로 인해 결과가
해상도가 전달된 값과 약간 다를 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

### getVerticalResolution() {#getVerticalResolution--}
```
public final double getVerticalResolution()
```


수직 해상도를 가져오거나 설정합니다. 참고: 반올림으로 인해 결과가
해상도가 전달된 값과 약간 다를 수 있습니다.


**Returns:**
double
### setVerticalResolution(double value) {#setVerticalResolution-double-}
```
public final void setVerticalResolution(double value)
```


수직 해상도를 가져오거나 설정합니다. 참고: 반올림으로 인해 결과가
해상도가 전달된 값과 약간 다를 수 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double |  |

