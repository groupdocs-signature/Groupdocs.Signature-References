---
title: "ImageSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 서명에 대한 검색 옵션을 나타냅니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.options.search/imagesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class ImageSearchOptions extends SearchOptions
```

이미지 서명에 대한 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageSearchOptions()](#ImageSearchOptions--) | ImageSearchOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getReturnContent()](#getReturnContent--) | 문서 페이지에서 서명의 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 문서 페이지에서 서명의 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [getMinContentSize()](#getMinContentSize--) | 0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최소 크기를 지정합니다. |
|
|  | [setMinContentSize(long value)](#setMinContentSize-long-) | 0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최소 크기를 지정합니다. |
|
|  | [getMaxContentSize()](#getMaxContentSize--) | 0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최대 크기를 지정합니다. |
|
|  | [setMaxContentSize(long value)](#setMaxContentSize-long-) | 0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최대 크기를 지정합니다. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent 속성이 활성화된 경우 이미지 서명의 반환된 콘텐츠 파일 유형을 지정합니다. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent 속성이 활성화된 경우 이미지 서명의 반환된 콘텐츠 파일 유형을 지정합니다. |
|
### ImageSearchOptions() {#ImageSearchOptions--}
```
public ImageSearchOptions()
```


ImageSearchOptions 클래스를 기본값으로 새 인스턴스를 초기화합니다.


### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


문서 페이지에서 서명의 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 이미지 서명 콘텐츠는 필요한 형식으로 원시 이미지 데이터를 유지합니다.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
기본적으로 이 옵션은 비활성화됩니다.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


문서 페이지에서 서명의 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 이미지 서명 콘텐츠는 필요한 형식으로 원시 이미지 데이터를 유지합니다.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
기본적으로 이 옵션은 비활성화됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getMinContentSize() {#getMinContentSize--}
```
public final long getMinContentSize()
```


0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최소 크기를 지정합니다.
기본값으로 이 플래그는 0으로 설정되며 검색 결과에 영향을 주지 않습니다.


**Returns:**
long
### setMinContentSize(long value) {#setMinContentSize-long-}
```
public final void setMinContentSize(long value)
```


0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최소 크기를 지정합니다.
기본값으로 이 플래그는 0으로 설정되며 검색 결과에 영향을 주지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### getMaxContentSize() {#getMaxContentSize--}
```
public final long getMaxContentSize()
```


0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최대 크기를 지정합니다.
기본값으로 이 플래그는 0으로 설정되며 검색 결과에 영향을 주지 않습니다.


**Returns:**
long
### setMaxContentSize(long value) {#setMaxContentSize-long-}
```
public final void setMaxContentSize(long value)
```


0이 아닌 값인 경우, 이 플래그는 검색 기준에 대한 이미지 최대 크기를 지정합니다.
기본값으로 이 플래그는 0으로 설정되며 검색 결과에 영향을 주지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | long |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent 속성이 활성화된 경우 이미지 서명의 반환된 콘텐츠 파일 유형을 지정합니다.
기본값으로 Null로 설정됩니다. 이는 원본 형식으로 이미지 콘텐츠를 반환한다는 의미입니다.
이 이미지 형식은 다음에서 지정됩니다.
ImageSignature.Format

가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 원본 형식의 이미지 콘텐츠가 반환됩니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent 속성이 활성화된 경우 이미지 서명의 반환된 콘텐츠 파일 유형을 지정합니다.
기본값으로 Null로 설정됩니다. 이는 원본 형식으로 이미지 콘텐츠를 반환한다는 의미입니다.
이 이미지 형식은 다음에서 지정됩니다.
ImageSignature.Format

가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 원본 형식의 이미지 콘텐츠가 반환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

