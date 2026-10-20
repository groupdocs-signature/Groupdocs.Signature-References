---
title: "ExportImageSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서를 이미지로 내보내기 위한 저장 옵션."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.options.saveoptions/exportimagesaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions), [com.groupdocs.signature.options.saveoptions.imagessaveoptions.ImageSaveOptions](../../com.groupdocs.signature.options.saveoptions.imagessaveoptions/imagesaveoptions)
```
public class ExportImageSaveOptions extends ImageSaveOptions
```

문서를 이미지로 내보내기 위한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ExportImageSaveOptions()](#ExportImageSaveOptions--) | ExportAsImageSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [ExportImageSaveOptions(int fileFormat)](#ExportImageSaveOptions-int-) | ExportAsImageSaveOptions 클래스의 새 인스턴스를 지정된 파일 형식으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPageNumber()](#getPageNumber--) | 내보내기용 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [setPageNumber(Integer value)](#setPageNumber-java.lang.Integer-) | 내보내기용 문서 페이지 번호를 가져오거나 설정합니다. |
|
|  | [getExportAllPages()](#getExportAllPages--) | 각 페이지를 내보내는 플래그입니다. |
|
|  | [setExportAllPages(boolean value)](#setExportAllPages-boolean-) | 각 페이지를 내보내는 플래그입니다. |
|
|  | [getPagesSetup()](#getPagesSetup--) | 서명할 페이지를 지정하는 옵션입니다. |
|
|  | [setPagesSetup(PagesSetup value)](#setPagesSetup-com.groupdocs.signature.options.PagesSetup-) | 서명할 페이지를 지정하는 옵션입니다. |
|
|  | [getPageColumns()](#getPageColumns--) | 내보낸 이미지의 열 수를 가져오거나 설정합니다. |
|
|  | [setPageColumns(int value)](#setPageColumns-int-) | 내보낸 이미지의 열 수를 가져오거나 설정합니다. |
|
|  | [getBorder()](#getBorder--) | 이미지 테두리 설정을 가져오거나 설정합니다. |
|
|  | [setBorder(Border value)](#setBorder-com.groupdocs.signature.domain.Border-) | 이미지 테두리 설정을 가져오거나 설정합니다. |
|
|  | [getTiffMultipage()](#getTiffMultipage--) | 문서 페이지를 Tiff 이미지의 서로 다른 프레임에 배치합니다. |
|
|  | [setTiffMultipage(boolean value)](#setTiffMultipage-boolean-) | 문서 페이지를 Tiff 이미지의 서로 다른 프레임에 배치합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### ExportImageSaveOptions() {#ExportImageSaveOptions--}
```
public ExportImageSaveOptions()
```


ExportAsImageSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### ExportImageSaveOptions(int fileFormat) {#ExportImageSaveOptions-int-}
```
public ExportImageSaveOptions(int fileFormat)
```


ExportAsImageSaveOptions 클래스의 새 인스턴스를 지정된 파일 형식으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 이미지 파일 형식. |
|

### getPageNumber() {#getPageNumber--}
```
public final Integer getPageNumber()
```


내보내기용 문서 페이지 번호를 가져오거나 설정합니다.
최소값은 1입니다.


**Returns:**
java.lang.Integer
### setPageNumber(Integer value) {#setPageNumber-java.lang.Integer-}
```
public final void setPageNumber(Integer value)
```


내보내기용 문서 페이지 번호를 가져오거나 설정합니다.
최소값은 1입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getExportAllPages() {#getExportAllPages--}
```
public final boolean getExportAllPages()
```


각 페이지를 내보내는 플래그입니다.


**Returns:**
boolean
### setExportAllPages(boolean value) {#setExportAllPages-boolean-}
```
public final void setExportAllPages(boolean value)
```


각 페이지를 내보내는 플래그입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPagesSetup() {#getPagesSetup--}
```
public final PagesSetup getPagesSetup()
```


서명할 페이지를 지정하는 옵션입니다.


**Returns:**
[PagesSetup](../../com.groupdocs.signature.options/pagessetup)
### setPagesSetup(PagesSetup value) {#setPagesSetup-com.groupdocs.signature.options.PagesSetup-}
```
public final void setPagesSetup(PagesSetup value)
```


서명할 페이지를 지정하는 옵션입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PagesSetup](../../com.groupdocs.signature.options/pagessetup) |  |

### getPageColumns() {#getPageColumns--}
```
public final int getPageColumns()
```


내보낸 이미지의 열 수를 가져오거나 설정합니다.
이미지를 한 줄에 배치해야 할 경우 이 속성을 사용하십시오.


**Returns:**
int
### setPageColumns(int value) {#setPageColumns-int-}
```
public final void setPageColumns(int value)
```


내보낸 이미지의 열 수를 가져오거나 설정합니다.
이미지를 한 줄에 배치해야 할 경우 이 속성을 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getBorder() {#getBorder--}
```
public final Border getBorder()
```


이미지 테두리 설정을 가져오거나 설정합니다. 기본값은 설정되지 않습니다.


**Returns:**
[Border](../../com.groupdocs.signature.domain/border)
### setBorder(Border value) {#setBorder-com.groupdocs.signature.domain.Border-}
```
public final void setBorder(Border value)
```


이미지 테두리 설정을 가져오거나 설정합니다. 기본값은 설정되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Border](../../com.groupdocs.signature.domain/border) |  |

### getTiffMultipage() {#getTiffMultipage--}
```
public final boolean getTiffMultipage()
```


문서 페이지를 Tiff 이미지의 서로 다른 프레임에 배치합니다.


**Returns:**
boolean
### setTiffMultipage(boolean value) {#setTiffMultipage-boolean-}
```
public final void setTiffMultipage(boolean value)
```


문서 페이지를 Tiff 이미지의 서로 다른 프레임에 배치합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
