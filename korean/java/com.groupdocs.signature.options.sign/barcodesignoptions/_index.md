---
title: "BarcodeSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "바코드 서명 옵션을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.options.sign/barcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class BarcodeSignOptions extends TextSignOptions
```

바코드 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [BarcodeSignOptions()](#BarcodeSignOptions--) | 기본값으로 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [BarcodeSignOptions(String text)](#BarcodeSignOptions-java.lang.String-) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [BarcodeSignOptions(String text, BarcodeType encodeType)](#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | Barcode 유형을 가져오거나 설정합니다. |
|
|  | [setEncodeType(BarcodeType value)](#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-) | Barcode 유형을 가져오거나 설정합니다. |
|
|  | [getForeColor()](#getForeColor--) | Barcode 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | Barcode 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | Barcode 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [getInnerMargins()](#getInnerMargins--) | Barcode 요소와 결과 이미지 테두리 사이의 간격을 가져오거나 설정합니다. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | Barcode 요소와 결과 이미지 테두리 사이의 간격을 가져오거나 설정합니다. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | 결과 바코드 이미지의 텍스트 정렬을 가져오거나 설정합니다. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 결과 바코드 이미지의 텍스트 정렬을 가져오거나 설정합니다. |
|
|  | [getReturnContent()](#getReturnContent--) | 문서 페이지에 배치된 서명의 바코드 이미지 내용을 가져오기 위한 플래그를 가져오거나 설정합니다. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 문서 페이지에 배치된 서명의 바코드 이미지 내용을 가져오기 위한 플래그를 가져오거나 설정합니다. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent 속성이 활성화된 경우 바코드 서명의 반환된 이미지 내용의 파일 형식을 지정합니다. |
|
|  | [validate()](#validate--) | 바코드 옵션 매개변수를 검증하기 위한 내부 메서드입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### BarcodeSignOptions() {#BarcodeSignOptions--}
```
public BarcodeSignOptions()
```


기본값으로 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.


### BarcodeSignOptions(String text) {#BarcodeSignOptions-java.lang.String-}
```
public BarcodeSignOptions(String text)
```


텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 바코드 텍스트 |
|

### BarcodeSignOptions(String text, BarcodeType encodeType) {#BarcodeSignOptions-java.lang.String-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public BarcodeSignOptions(String text, BarcodeType encodeType)
```


텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 바코드 텍스트 |
|
|  | encodeType | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) | 바코드 인코드 유형은 [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) 를 참조하십시오. |
|

### getEncodeType() {#getEncodeType--}
```
public final BarcodeType getEncodeType()
```


Barcode 유형을 가져오거나 설정합니다.


**Returns:**
[BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype)
### setEncodeType(BarcodeType value) {#setEncodeType-com.groupdocs.signature.domain.barcodes.BarcodeType-}
```
public final void setEncodeType(BarcodeType value)
```


Barcode 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [BarcodeType](../../com.groupdocs.signature.domain.barcodes/barcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


Barcode 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


Barcode 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


Barcode 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


Barcode 요소와 결과 이미지 테두리 사이의 간격을 가져오거나 설정합니다.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


Barcode 요소와 결과 이미지 테두리 사이의 간격을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


결과 바코드 이미지의 텍스트 정렬을 가져오거나 설정합니다.
기본값은 None입니다.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


결과 바코드 이미지의 텍스트 정렬을 가져오거나 설정합니다.
기본값은 None입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


문서 페이지에 배치된 서명의 바코드 이미지 내용을 가져오기 위한 플래그를 가져오거나 설정합니다.
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


문서 페이지에 배치된 서명의 바코드 이미지 내용을 가져오기 위한 플래그를 가져오거나 설정합니다.
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
([BarcodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/barcodesignature#getFormat))
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 .png 형식의 바코드 이미지 내용이 반환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### validate() {#validate--}
```
public void validate()
```


바코드 옵션 매개변수를 검증하기 위한 내부 메서드입니다.


### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
