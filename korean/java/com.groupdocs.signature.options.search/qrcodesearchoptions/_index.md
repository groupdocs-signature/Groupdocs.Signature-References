---
title: "QrCodeSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "QR 코드 서명에 대한 추상 검색 옵션을 나타냅니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.options.search/qrcodesearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class QrCodeSearchOptions extends SearchOptions
```

QR 코드 서명에 대한 추상 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [QrCodeSearchOptions()](#QrCodeSearchOptions--) | QRCodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다. |
|
|  | [QrCodeSearchOptions(QrCodeType encodeType, String text)](#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-) | QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR 코드 검색을 위한 Encode Type 속성을 지정합니다. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR 코드 검색을 위한 Encode Type 속성을 지정합니다. |
|
|  | [getText()](#getText--) | QR-Code 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다. |
|
|  | [setText(String value)](#setText-java.lang.String-) | QR-Code 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다. |
|
|  | [getMatchType()](#getMatchType--) | QR-Code 텍스트 매치 유형 검색을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | QR-Code 텍스트 매치 유형 검색을 가져오거나 설정합니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [getReturnContent()](#getReturnContent--) | 문서 페이지에서 서명의 QR-Code 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 문서 페이지에서 서명의 QR-Code 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다. |
|
### QrCodeSearchOptions() {#QrCodeSearchOptions--}
```
public QrCodeSearchOptions()
```


QRCodeSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### QrCodeSearchOptions(QrCodeType encodeType) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSearchOptions(QrCodeType encodeType)
```


QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 값으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code 인코드 유형을 지정합니다. |
|

### QrCodeSearchOptions(QrCodeType encodeType, String text) {#QrCodeSearchOptions-com.groupdocs.signature.domain.qrcodes.QrCodeType-java.lang.String-}
```
public QrCodeSearchOptions(QrCodeType encodeType, String text)
```


QRCodeSearchOptions 클래스의 새 인스턴스를 인코드 유형 및 텍스트 값으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QR-Code 인코드 유형을 지정합니다. |
|
|  | 텍스트 | java.lang.String | QR-Code 서명의 텍스트를 설정합니다. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR 코드 검색을 위한 Encode Type 속성을 지정합니다.
이 값이 설정되지 않은 경우, 지원되는 모든 QR-Code 유형에 대해 검색이 수행됩니다.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR 코드 검색을 위한 Encode Type 속성을 지정합니다.
이 값이 설정되지 않은 경우, 지원되는 모든 QR-Code 유형에 대해 검색이 수행됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getText() {#getText--}
```
public final String getText()
```


QR-Code 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다.


**Returns:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


QR-Code 서명 텍스트를 검색하고 일치시켜야 하는 경우 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


QR-Code 텍스트 매치 유형 검색을 가져오거나 설정합니다. 이는 Text 속성이 설정된 경우에만 사용됩니다.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


QR-Code 텍스트 매치 유형 검색을 가져오거나 설정합니다. 이는 Text 속성이 설정된 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### getReturnContent() {#getReturnContent--}
```
public final boolean getReturnContent()
```


문서 페이지에서 서명의 QR-Code 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 QR-Code 서명 이미지 콘텐츠는 필요한 형식으로 원시 이미지 데이터를 유지합니다.
ReturnContentType
(#getReturnContentType.getReturnContentType/#setReturnContentType(FileType).setReturnContentType(FileType)).
기본적으로 이 옵션은 비활성화됩니다.


**Returns:**
boolean
### setReturnContent(boolean value) {#setReturnContent-boolean-}
```
public final void setReturnContent(boolean value)
```


문서 페이지에서 서명의 QR-Code 이미지 내용을 가져오는 플래그를 가져오거나 설정합니다.
이 플래그가 true로 설정되면 QR-Code 서명 이미지 콘텐츠는 필요한 형식으로 원시 이미지 데이터를 유지합니다.
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


ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다.
기본값은 Null로 설정됩니다. 이는 QR-Code 이미지 콘텐츠를 원본 형식으로 반환함을 의미합니다.
이 이미지 형식은 다음에서 지정됩니다.
QrCodeSignature.Format
()
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않는 경우 원본 .png의 QR-Code 이미지 내용이 반환됩니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setReturnContentType(FileType value) {#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setReturnContentType(FileType value)
```


ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다.
기본값은 Null로 설정됩니다. 이는 QR-Code 이미지 콘텐츠를 원본 형식으로 반환함을 의미합니다.
이 이미지 형식은 다음에서 지정됩니다.
QrCodeSignature.Format
()
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않는 경우 원본 .png의 QR-Code 이미지 내용이 반환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

