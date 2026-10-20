---
title: "BarcodeSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "Barcode 서명을 위한 추상 검색 옵션을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.options.search/barcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class BarcodeSearchOptions extends SearchOptions
```

Barcode 서명을 위한 추상 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [BarcodeSearchOptions()](#BarcodeSearchOptions--) | SearchBarcodeOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-) | SearchBarcodeOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다. |
|
|  | [BarcodeSearchOptions(BarcodeType encodeType, String text)](#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-) | SearchBarcodeOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | 바코드를 검색하기 위해 Encode Type 속성을 지정합니다. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 바코드를 검색하기 위해 Encode Type 속성을 지정합니다. |
|
|  | [getText()](#getText--) | Barcode 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | Barcode 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다. |
|
|  | [getMatchType()](#getMatchType--) | Barcode 텍스트 매치 유형 검색을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | Barcode 텍스트 매치 유형 검색을 가져오거나 설정합니다. |
|
|  | [getReturnContent()](#getReturnContent--) | 문서 페이지에서 서명의 Barcode 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 문서 페이지에서 서명의 Barcode 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다. |
|
### BarcodeSearchOptions() {#BarcodeSearchOptions--}
```
public BarcodeSearchOptions()
```


SearchBarcodeOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### BarcodeSearchOptions(BarcodeType encodeType) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSearchOptions(BarcodeType encodeType)
```


SearchBarcodeOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode 인코드 유형을 지정합니다. |
|

### BarcodeSearchOptions(BarcodeType encodeType, String text) {#BarcodeSearchOptions-com.groupdocs.signature.domain.barcodes.BarcodeType-java.lang.String-}
```
public BarcodeSearchOptions(BarcodeType encodeType, String text)
```


SearchBarcodeOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | Barcode 인코드 유형을 지정합니다. |
|
|  | 텍스트 | java.lang.String | Barcode 서명의 텍스트를 설정합니다. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


바코드를 검색하기 위해 Encode Type 속성을 지정합니다.
이 값이 설정되지 않은 경우, 지원되는 모든 Barcode 유형에 대해 검색이 수행됩니다.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


바코드를 검색하기 위해 Encode Type 속성을 지정합니다.
이 값이 설정되지 않은 경우, 지원되는 모든 Barcode 유형에 대해 검색이 수행됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


Barcode 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Barcode 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


Barcode 텍스트 매치 유형 검색을 가져오거나 설정합니다. 이는 Text 속성이 설정된 경우에만 사용됩니다.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


Barcode 텍스트 매치 유형 검색을 가져오거나 설정합니다. 이는 Text 속성이 설정된 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


문서 페이지에서 서명의 Barcode 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 바코드 서명 이미지 내용은 필요한 형식으로 원시 이미지 데이터를 유지합니다.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
기본적으로 이 옵션은 비활성화됩니다.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


문서 페이지에서 서명의 Barcode 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 바코드 서명 이미지 내용은 필요한 형식으로 원시 이미지 데이터를 유지합니다.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
기본적으로 이 옵션은 비활성화됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getReturnContentType() {#getReturnContentType--}
```
public final FileType getReturnContentType()
```


ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다.
기본적으로 Null로 설정됩니다. 이는 바코드 이미지 내용을 원래 형식으로 반환한다는 의미입니다.
이 이미지 형식은 다음에서 지정됩니다.
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 .png 형식의 바코드 이미지 내용이 반환됩니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다.
기본적으로 Null로 설정됩니다. 이는 바코드 이미지 내용을 원래 형식으로 반환한다는 의미입니다.
이 이미지 형식은 다음에서 지정됩니다.
BarcodeSignature.Format
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat)})
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 .png 형식의 바코드 이미지 내용이 반환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

