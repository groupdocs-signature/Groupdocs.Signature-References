---
title: "GifSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 문서에 대한 GIF 형식 저장 옵션."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/gifsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class GifSaveOptions extends ImageSaveOptions
```

이미지 문서에 대한 GIF 형식 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [GifSaveOptions()](#GifSaveOptions--) | 기본값으로 GifSaveOptions를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBackgroundColorIndex()](#getBackgroundColorIndex--) | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
|
|  | [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | GIF 배경 색 인덱스를 가져오거나 설정합니다. |
|
|  | [getColorResolution()](#getColorResolution--) | GIF 색 해상도를 가져오거나 설정합니다. |
|
|  | [setColorResolution(byte value)](#setColorResolution-byte-) | GIF 색 해상도를 가져오거나 설정합니다. |
|
|  | [getDoPaletteCorrection()](#getDoPaletteCorrection--) | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setDoPaletteCorrection(boolean value)](#setDoPaletteCorrection-boolean-) | 팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [hasTrailer()](#hasTrailer--) | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setTrailer(boolean value)](#setTrailer-boolean-) | GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [getInterlaced()](#getInterlaced--) | 이미지를 인터레이스해야 하는 경우 true. |
|
|  | [setInterlaced(boolean value)](#setInterlaced-boolean-) | 이미지를 인터레이스해야 하는 경우 true. |
|
|  | [isPaletteSorted()](#isPaletteSorted--) | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | 팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [getPixelAspectRatio()](#getPixelAspectRatio--) | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
|
|  | [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | GIF 픽셀 종횡비를 가져오거나 설정합니다. |
|
### GifSaveOptions() {#GifSaveOptions--}
```
public GifSaveOptions()
```


기본값으로 GifSaveOptions를 생성합니다.


### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


GIF 배경 색 인덱스를 가져오거나 설정합니다.


**Returns:**
byte
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


GIF 배경 색 인덱스를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### getColorResolution() {#getColorResolution--}
```
public byte getColorResolution()
```


GIF 색 해상도를 가져오거나 설정합니다.

<br />

*** ** * ** ***

Color Resolution - 원본 이미지에서 사용할 수 있는 기본 색당 비트 수에서 1을 뺀 값입니다. 이 값은 그래픽에서 선택된 색상이 아닌 전체 팔레트의 크기를 나타냅니다. 예를 들어, 이 필드의 값이 3이면 원본 이미지의 팔레트는 이미지를 만들기 위해 기본 색당 4비트를 가지고 있었음을 의미합니다. 이 값은 전체 팔레트의 모든 색상이 소스 머신에 존재하지 않더라도 원본 팔레트의 풍부함을 표시하도록 설정해야 합니다.

<br />



**Returns:**
byte
### setColorResolution(byte value) {#setColorResolution-byte-}
```
public void setColorResolution(byte value)
```


GIF 색 해상도를 가져오거나 설정합니다.

<br />

*** ** * ** ***

Color Resolution - 원본 이미지에서 사용할 수 있는 기본 색당 비트 수에서 1을 뺀 값입니다. 이 값은 그래픽에서 선택된 색상이 아닌 전체 팔레트의 크기를 나타냅니다. 예를 들어, 이 필드의 값이 3이면 원본 이미지의 팔레트는 이미지를 만들기 위해 기본 색당 4비트를 가지고 있었음을 의미합니다. 이 값은 전체 팔레트의 모든 색상이 소스 머신에 존재하지 않더라도 원본 팔레트의 풍부함을 표시하도록 설정해야 합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### getDoPaletteCorrection() {#getDoPaletteCorrection--}
```
public boolean getDoPaletteCorrection()
```


팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다.

<br />

*** ** * ** ***

팔레트 보정은 이미지가 GIF로 내보내질 때마다 원본 이미지 색상이 최적의 일치 팔레트를 만들기 위해 분석된다는 의미입니다(이미지 팔레트가 없거나 옵션에 지정되지 않은 경우). 분석 과정에는 시간이 걸리지만, 출력 이미지가 최적의 색 팔레트를 갖게 되어 시각적으로 더 나은 결과를 제공합니다.

<br />



**Returns:**
boolean
### setDoPaletteCorrection(boolean value) {#setDoPaletteCorrection-boolean-}
```
public void setDoPaletteCorrection(boolean value)
```


팔레트 보정이 적용되는지 여부를 나타내는 값을 가져오거나 설정합니다.

<br />

*** ** * ** ***

팔레트 보정은 이미지가 GIF로 내보내질 때마다 원본 이미지 색상이 최적의 일치 팔레트를 만들기 위해 분석된다는 의미입니다(이미지 팔레트가 없거나 옵션에 지정되지 않은 경우). 분석 과정에는 시간이 걸리지만, 출력 이미지가 최적의 색 팔레트를 갖게 되어 시각적으로 더 나은 결과를 제공합니다.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.


**Returns:**
boolean
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


GIF에 트레일러가 있는지 여부를 나타내는 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


이미지를 인터레이스해야 하는 경우 true.


**Returns:**
boolean
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


이미지를 인터레이스해야 하는 경우 true.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다.


**Returns:**
boolean
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


팔레트 항목이 정렬되는지 여부를 나타내는 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


GIF 픽셀 종횡비를 가져오거나 설정합니다.

<br />

*** ** * ** ***

Pixel Aspect Ratio - 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 요소입니다. 필드 값이 0이 아니면, 다음 공식에 따라 종횡비 근사값이 계산됩니다: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 1/64 단위로 가장 넓은 픽셀 4:1부터 가장 높은 픽셀 1:4까지 지정할 수 있습니다. 값: 0 - 종횡비 정보가 제공되지 않음. 1..255 - 계산에 사용되는 값.

<br />



**Returns:**
byte
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


GIF 픽셀 종횡비를 가져오거나 설정합니다.

<br />

*** ** * ** ***

Pixel Aspect Ratio - 원본 이미지에서 픽셀의 종횡비 근사값을 계산하는 데 사용되는 요소입니다. 필드 값이 0이 아니면, 다음 공식에 따라 종횡비 근사값이 계산됩니다: Aspect Ratio = (Pixel Aspect Ratio + 15) / 64. Pixel Aspect Ratio는 픽셀의 너비를 높이로 나눈 값으로 정의됩니다. 이 필드의 값 범위는 1/64 단위로 가장 넓은 픽셀 4:1부터 가장 높은 픽셀 1:4까지 지정할 수 있습니다. 값: 0 - 종횡비 정보가 제공되지 않음. 1..255 - 계산에 사용되는 값.

<br />



**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

