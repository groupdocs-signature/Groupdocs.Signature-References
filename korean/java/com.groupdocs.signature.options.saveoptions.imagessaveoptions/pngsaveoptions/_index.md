---
title: "PngSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 문서에 대한 PNG 저장 옵션."
type: docs
weight: 22
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/pngsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class PngSaveOptions extends ImageSaveOptions
```

이미지 문서에 대한 PNG 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PngSaveOptions()](#PngSaveOptions--) | 기본값으로 PngSaveOptions를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBitDepth()](#getBitDepth--) | 비트 깊이. |
|
|  | [setBitDepth(byte value)](#setBitDepth-byte-) | 비트 깊이. |
|
|  | [getColorType()](#getColorType--) | 형식의 유형을 가져오거나 설정합니다 |
PngColorType
.
|
|  | [setColorType(int value)](#setColorType-int-) | 형식의 유형을 가져오거나 설정합니다 |
PngColorType
.
|
|  | [getCompressionLevel()](#getCompressionLevel--) | png 이미지 압축 수준은 0-9 범위이며, 9는 최대 압축을 의미합니다 |
그리고 0은 저장 모드입니다.
|
|  | [setCompressionLevel(int value)](#setCompressionLevel-int-) | png 이미지 압축 수준은 0-9 범위이며, 9는 최대 압축을 의미합니다 |
그리고 0은 저장 모드입니다.
|
|  | [getFilterType()](#getFilterType--) | 필터 유형을 가져오거나 설정합니다 |
PngFilterType
png 파일 저장 과정에서 사용됩니다.
|
|  | [setFilterType(int value)](#setFilterType-int-) | 필터 유형을 가져오거나 설정합니다 |
PngFilterType
png 파일 저장 과정에서 사용됩니다.
|
|  | [getProgressive()](#getProgressive--) | 이 PngSaveOptions가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
|  | [setProgressive(boolean value)](#setProgressive-boolean-) | 이 PngSaveOptions가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다. |
|
### PngSaveOptions() {#PngSaveOptions--}
```
public PngSaveOptions()
```


기본값으로 PngSaveOptions를 생성합니다.


### getBitDepth() {#getBitDepth--}
```
public byte getBitDepth()
```


비트 깊이.


**Returns:**
byte
### setBitDepth(byte value) {#setBitDepth-byte-}
```
public void setBitDepth(byte value)
```


비트 깊이.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


형식의 유형을 가져오거나 설정합니다
PngColorType
.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


형식의 유형을 가져오거나 설정합니다
PngColorType
.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public int getCompressionLevel()
```


png 이미지 압축 수준은 0-9 범위이며, 9는 최대 압축을 의미합니다
그리고 0은 저장 모드입니다.


**Returns:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public void setCompressionLevel(int value)
```


png 이미지 압축 수준은 0-9 범위이며, 9는 최대 압축을 의미합니다
그리고 0은 저장 모드입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFilterType() {#getFilterType--}
```
public int getFilterType()
```


필터 유형을 가져오거나 설정합니다
PngFilterType
png 파일 저장 과정에서 사용됩니다.


**Returns:**
int
### setFilterType(int value) {#setFilterType-int-}
```
public void setFilterType(int value)
```


필터 유형을 가져오거나 설정합니다
PngFilterType
png 파일 저장 과정에서 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getProgressive() {#getProgressive--}
```
public boolean getProgressive()
```


이 PngSaveOptions가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다.


**Returns:**
boolean
### setProgressive(boolean value) {#setProgressive-boolean-}
```
public void setProgressive(boolean value)
```


이 PngSaveOptions가 진행형인지 여부를 나타내는 값을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

