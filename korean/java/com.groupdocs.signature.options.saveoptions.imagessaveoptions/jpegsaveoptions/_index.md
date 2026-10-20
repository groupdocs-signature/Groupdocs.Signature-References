---
title: "JpegSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 문서에 대한 JPEG 저장 옵션."
type: docs
weight: 19
url: /ko/java/com.groupdocs.signature.options.saveoptions.imagessaveoptions/jpegsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class JpegSaveOptions extends ImageSaveOptions
```

이미지 문서에 대한 JPEG 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [JpegSaveOptions()](#JpegSaveOptions--) | 기본값으로 JpegSaveOptions를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getBitsPerChannel()](#getBitsPerChannel--) | 무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다. |
|
|  | [setBitsPerChannel(byte value)](#setBitsPerChannel-byte-) | 무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다. |
|
|  | [getColorType()](#getColorType--) | jpeg 이미지의 색상 유형을 가져오거나 설정합니다. |
|
|  | [setColorType(int value)](#setColorType-int-) | jpeg 이미지의 색상 유형을 가져오거나 설정합니다. |
|
|  | [getComment()](#getComment--) | jpeg 파일 주석을 가져오거나 설정합니다. |
|
|  | [setComment(String value)](#setComment-java.lang.String-) | jpeg 파일 주석을 가져오거나 설정합니다. |
|
|  | [getCompressionType()](#getCompressionType--) | 압축 유형을 가져오거나 설정합니다. |
|
|  | [setCompressionType(int value)](#setCompressionType-int-) | 압축 유형을 가져오거나 설정합니다. |
|
|  | [getQuality()](#getQuality--) | 이미지 품질을 가져오거나 설정합니다. |
|
|  | [setQuality(int value)](#setQuality-int-) | 이미지 품질을 가져오거나 설정합니다. |
|
|  | [getSampleRoundingMode()](#getSampleRoundingMode--) | 8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다. |
JpegOptions.BitsPerChannel.
|
|  | [setSampleRoundingMode(int value)](#setSampleRoundingMode-int-) | 8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다. |
JpegOptions.BitsPerChannel.
|
|  | [getFileFormat()](#getFileFormat--) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
### JpegSaveOptions() {#JpegSaveOptions--}
```
public JpegSaveOptions()
```


기본값으로 JpegSaveOptions를 생성합니다.


### getBitsPerChannel() {#getBitsPerChannel--}
```
public byte getBitsPerChannel()
```


무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다.
이제 채널당 2비트에서 8비트까지 지원합니다.


**Returns:**
byte
### setBitsPerChannel(byte value) {#setBitsPerChannel-byte-}
```
public void setBitsPerChannel(byte value)
```


무손실 jpeg 이미지의 채널당 비트를 가져오거나 설정합니다.
이제 채널당 2비트에서 8비트까지 지원합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte |  |

### getColorType() {#getColorType--}
```
public int getColorType()
```


jpeg 이미지의 색상 유형을 가져오거나 설정합니다.


**Returns:**
int
### setColorType(int value) {#setColorType-int-}
```
public void setColorType(int value)
```


jpeg 이미지의 색상 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getComment() {#getComment--}
```
public String getComment()
```


jpeg 파일 주석을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


jpeg 파일 주석을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCompressionType() {#getCompressionType--}
```
public int getCompressionType()
```


압축 유형을 가져오거나 설정합니다.


**Returns:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public void setCompressionType(int value)
```


압축 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getQuality() {#getQuality--}
```
public int getQuality()
```


이미지 품질을 가져오거나 설정합니다.


**Returns:**
int
### setQuality(int value) {#setQuality-int-}
```
public void setQuality(int value)
```


이미지 품질을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSampleRoundingMode() {#getSampleRoundingMode--}
```
public int getSampleRoundingMode()
```


8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다.
JpegOptions.BitsPerChannel.


**Returns:**
int
### setSampleRoundingMode(int value) {#setSampleRoundingMode-int-}
```
public void setSampleRoundingMode(int value)
```


8비트 값을 n비트 값에 맞추기 위한 샘플 반올림 모드를 가져오거나 설정합니다.
JpegOptions.BitsPerChannel.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


서명된 문서의 파일 형식을 가져오거나 설정합니다. 이 옵션 클래스에서는 사용되지 않아 숨겨져 있습니다.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


서명된 문서의 파일 형식을 가져오거나 설정합니다. 이 옵션 클래스에서는 사용되지 않아 숨겨져 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

