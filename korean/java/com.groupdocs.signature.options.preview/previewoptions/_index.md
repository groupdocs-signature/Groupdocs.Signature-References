---
title: "PreviewOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 미리보기 옵션을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.preview/previewoptions/
---
**Inheritance:**
java.lang.Object
```
public class PreviewOptions
```

문서 미리보기 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-) | PreviewOptions 객체를 초기화합니다. |
|
|  | [PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)](#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-) | PreviewOptions 객체를 초기화합니다. |
|
|  | [PreviewOptions(String filePathFormat, int[] pageNumbers)](#PreviewOptions-java.lang.String-int...-) | PreviewOptions 객체를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getWidth()](#getWidth--) | 미리보기 이미지의 너비를 가져오거나 설정합니다. |
|
|  | [setWidth(int value)](#setWidth-int-) | 미리보기 이미지의 너비를 가져오거나 설정합니다. |
|
|  | [getHeight()](#getHeight--) | 미리보기 이미지의 높이를 가져오거나 설정합니다. |
|
|  | [setHeight(int value)](#setHeight-int-) | 미리보기 이미지의 높이를 가져오거나 설정합니다. |
|
|  | [getPageNumbers()](#getPageNumbers--) | 미리보기 이미지의 페이지 번호를 가져오거나 설정합니다. |
|
|  | [setPageNumbers(int[] value)](#setPageNumbers-int---) | 미리보기 이미지의 페이지 번호를 가져오거나 설정합니다. |
|
|  | [getPreviewFormat()](#getPreviewFormat--) | 미리보기 이미지 형식을 가져오거나 설정합니다. |
|
|  | [setPreviewFormat(int value)](#setPreviewFormat-int-) | 미리보기 이미지 형식을 가져오거나 설정합니다. |
|
|  | [getHideSignatures()](#getHideSignatures--) | 페이지 미리보기 이미지에서 서명을 숨기는 플래그를 가져오거나 설정합니다. |
|
|  | [setHideSignatures(boolean value)](#setHideSignatures-boolean-) | 페이지 미리보기 이미지에서 서명을 숨기는 플래그를 가져오거나 설정합니다. |
|
|  | [getResolution()](#getResolution--) | 미리보기 이미지의 해상도를 DPI(인치당 점) 단위로 가져옵니다. |
|
|  | [setResolution(int value)](#setResolution-int-) | 미리보기 이미지의 해상도를 DPI(인치당 점) 단위로 설정합니다. |
|
### PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageStreamFactory-int...-}
```
public PreviewOptions(PageStreamFactory pageStreamFactory, int[] pageNumbers)
```


PreviewOptions 객체를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageStreamFactory | [PageStreamFactory](../../com.groupdocs.signature.options/pagestreamfactory) | 출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 인터페이스입니다. |
|
|  | pageNumbers | int[] | 원하는 페이지 번호 |
|

### PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers) {#PreviewOptions-com.groupdocs.signature.options.PageDataStreamFactory-int...-}
```
public PreviewOptions(PageDataStreamFactory pageDataStreamFactory, int[] pageNumbers)
```


PreviewOptions 객체를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | pageDataStreamFactory | [PageDataStreamFactory](../../com.groupdocs.signature.options/pagedatastreamfactory) | 출력 페이지 미리보기 스트림을 생성하는 메서드를 정의하는 인터페이스입니다. |
|
| pageNumbers | int[] |  |

### PreviewOptions(String filePathFormat, int[] pageNumbers) {#PreviewOptions-java.lang.String-int...-}
```
public PreviewOptions(String filePathFormat, int[] pageNumbers)
```


PreviewOptions 객체를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | filePathFormat | java.lang.String | 출력 파일 경로. |
|
|  | pageNumbers | int[] | 원하는 페이지 번호 |
|

### getWidth() {#getWidth--}
```
public final int getWidth()
```


미리보기 이미지의 너비를 가져오거나 설정합니다.


**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public final void setWidth(int value)
```


미리보기 이미지의 너비를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHeight() {#getHeight--}
```
public final int getHeight()
```


미리보기 이미지의 높이를 가져오거나 설정합니다.


**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public final void setHeight(int value)
```


미리보기 이미지의 높이를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getPageNumbers() {#getPageNumbers--}
```
public final int[] getPageNumbers()
```


미리보기 이미지의 페이지 번호를 가져오거나 설정합니다.


**Returns:**
int[]
### setPageNumbers(int[] value) {#setPageNumbers-int---}
```
public final void setPageNumbers(int[] value)
```


미리보기 이미지의 페이지 번호를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int[] |  |

### getPreviewFormat() {#getPreviewFormat--}
```
public final int getPreviewFormat()
```


미리보기 이미지 형식을 가져오거나 설정합니다.


**Returns:**
int
### setPreviewFormat(int value) {#setPreviewFormat-int-}
```
public final void setPreviewFormat(int value)
```


미리보기 이미지 형식을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHideSignatures() {#getHideSignatures--}
```
public final boolean getHideSignatures()
```


페이지 미리보기 이미지에서 서명을 숨기는 플래그를 가져오거나 설정합니다.
IsSignature로 표시된 서명만 생성된 문서 페이지 이미지에서 숨겨집니다.


**Returns:**
boolean
### setHideSignatures(boolean value) {#setHideSignatures-boolean-}
```
public final void setHideSignatures(boolean value)
```


페이지 미리보기 이미지에서 서명을 숨기는 플래그를 가져오거나 설정합니다.
IsSignature로 표시된 서명만 생성된 문서 페이지 이미지에서 숨겨집니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getResolution() {#getResolution--}
```
public final int getResolution()
```


미리보기 이미지의 해상도를 DPI(인치당 점) 단위로 가져옵니다.


**Returns:**
int
### setResolution(int value) {#setResolution-int-}
```
public final void setResolution(int value)
```


미리보기 이미지의 해상도를 DPI(인치당 점) 단위로 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

