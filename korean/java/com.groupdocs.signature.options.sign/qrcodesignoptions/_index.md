---
title: "QrCodeSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "QR-Code 서명 옵션을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.options.sign/qrcodesignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.TextSignOptions](../../com.groupdocs.signature.options.sign/textsignoptions)
```
public class QrCodeSignOptions extends TextSignOptions
```

QR-Code 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [QrCodeSignOptions()](#QrCodeSignOptions--) | QrCodeSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [QrCodeSignOptions(String text)](#QrCodeSignOptions-java.lang.String-) | QRCodeSignOptions 클래스의 새 인스턴스를 텍스트와 함께 초기화합니다. |
|
|  | [QrCodeSignOptions(String text, QrCodeType encodeType)](#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QRCode 유형을 가져오거나 설정합니다. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QRCode 유형을 가져오거나 설정합니다. |
|
|  | [getForeColor()](#getForeColor--) | QR-Code 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [setForeColor(Color value)](#setForeColor-java.awt.Color-) | QR-Code 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [setForeColor(String value)](#setForeColor-java.lang.String-) | QR-Code 바의 전경 색상을 가져오거나 설정합니다. |
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다.
|
|  | [getInnerMargins()](#getInnerMargins--) | QRCode 요소와 결과 이미지 경계 사이의 간격을 가져오거나 설정합니다. |
|
|  | [setInnerMargins(Padding value)](#setInnerMargins-com.groupdocs.signature.domain.Padding-) | QRCode 요소와 결과 이미지 경계 사이의 간격을 가져오거나 설정합니다. |
|
|  | [getCodeTextAlignment()](#getCodeTextAlignment--) | 결과 QR-code 이미지에서 텍스트 정렬을 가져오거나 설정합니다. |
|
|  | [setCodeTextAlignment(int value)](#setCodeTextAlignment-int-) | 결과 QR-code 이미지에서 텍스트 정렬을 가져오거나 설정합니다. |
|
|  | [getLogoFilePath()](#getLogoFilePath--) | QR-code 로고 이미지 파일 이름을 가져오거나 설정합니다. |
|
|  | [setLogoFilePath(String value)](#setLogoFilePath-java.lang.String-) | QR-code 로고 이미지 파일 이름을 가져오거나 설정합니다. |
|
|  | [getLogoStream()](#getLogoStream--) | QR-code 로고 이미지 스트림을 가져오거나 설정합니다. |
|
|  | [setLogoStream(InputStream value)](#setLogoStream-java.io.InputStream-) | QR-code 로고 이미지 스트림을 가져오거나 설정합니다. |
|
|  | [getData()](#getData--) | QR-Code 콘텐츠에 직렬화할 사용자 정의 객체를 가져오거나 설정합니다. |
|
|  | [setData(Object value)](#setData-java.lang.Object-) | QR-Code 콘텐츠에 직렬화할 사용자 정의 객체를 가져오거나 설정합니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [getReturnContent()](#getReturnContent--) | 문서 페이지에 삽입된 서명의 QR-Code 이미지 콘텐츠를 가져오기 위한 플래그를 가져오거나 설정합니다. |
|
|  | [setReturnContent(boolean value)](#setReturnContent-boolean-) | 문서 페이지에 삽입된 서명의 QR-Code 이미지 콘텐츠를 가져오기 위한 플래그를 가져오거나 설정합니다. |
|
|  | [getReturnContentType()](#getReturnContentType--) | ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다. |
|
|  | [setReturnContentType(FileType value)](#setReturnContentType-com.groupdocs.signature.domain.documentpreview.FileType-) | ReturnContent 속성이 활성화된 경우 QR-Code 서명의 반환된 이미지 콘텐츠 파일 유형을 지정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
| [signature()](#signature--) |  |
### QrCodeSignOptions() {#QrCodeSignOptions--}
```
public QrCodeSignOptions()
```


QrCodeSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### QrCodeSignOptions(String text) {#QrCodeSignOptions-java.lang.String-}
```
public QrCodeSignOptions(String text)
```


QRCodeSignOptions 클래스의 새 인스턴스를 텍스트와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 서명 텍스트. |
|

### QrCodeSignOptions(String text, QrCodeType encodeType) {#QrCodeSignOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeSignOptions(String text, QrCodeType encodeType)
```


텍스트와 함께 BarcodeSignOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | QRCode 텍스트 |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | QRCode 인코드 유형은 [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) 를 참조하십시오. |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QRCode 유형을 가져오거나 설정합니다.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QRCode 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getForeColor() {#getForeColor--}
```
public Color getForeColor()
```


QR-Code 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Returns:**
java.awt.Color
### setForeColor(Color value) {#setForeColor-java.awt.Color-}
```
public void setForeColor(Color value)
```


QR-Code 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.awt.Color |  |

### setForeColor(String value) {#setForeColor-java.lang.String-}
```
public void setForeColor(String value)
```


QR-Code 바의 전경 색상을 가져오거나 설정합니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getInnerMargins() {#getInnerMargins--}
```
public final Padding getInnerMargins()
```


QRCode 요소와 결과 이미지 경계 사이의 간격을 가져오거나 설정합니다.


**Returns:**
[Padding](../../com.groupdocs.signature.domain/padding)
### setInnerMargins(Padding value) {#setInnerMargins-com.groupdocs.signature.domain.Padding-}
```
public final void setInnerMargins(Padding value)
```


QRCode 요소와 결과 이미지 경계 사이의 간격을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Padding](../../com.groupdocs.signature.domain/padding) |  |

### getCodeTextAlignment() {#getCodeTextAlignment--}
```
public final int getCodeTextAlignment()
```


결과 QR-code 이미지에서 텍스트 정렬을 가져오거나 설정합니다.
기본값은 None입니다.


**Returns:**
int
### setCodeTextAlignment(int value) {#setCodeTextAlignment-int-}
```
public final void setCodeTextAlignment(int value)
```


결과 QR-code 이미지에서 텍스트 정렬을 가져오거나 설정합니다.
기본값은 None입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getLogoFilePath() {#getLogoFilePath--}
```
public final String getLogoFilePath()
```


QR-code 로고 이미지 파일 이름을 가져오거나 설정합니다.
이 속성은 LogoStream이 지정되지 않은 경우에만 사용됩니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Returns:**
java.lang.String
### setLogoFilePath(String value) {#setLogoFilePath-java.lang.String-}
```
public final void setLogoFilePath(String value)
```


QR-code 로고 이미지 파일 이름을 가져오거나 설정합니다.
이 속성은 LogoStream이 지정되지 않은 경우에만 사용됩니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLogoStream() {#getLogoStream--}
```
public final InputStream getLogoStream()
```


QR-code 로고 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 LogoGuid 대신 사용됩니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Returns:**
java.io.InputStream
### setLogoStream(InputStream value) {#setLogoStream-java.io.InputStream-}
```
public final void setLogoStream(InputStream value)
```


QR-code 로고 이미지 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 LogoGuid 대신 사용됩니다.
이 속성을 사용하면 검증에 문제가 발생할 수 있습니다. 신중하게 사용하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

### getData() {#getData--}
```
public final Object getData()
```


QR-Code 콘텐츠에 직렬화할 사용자 정의 객체를 가져오거나 설정합니다.


**Returns:**
java.lang.Object
### setData(Object value) {#setData-java.lang.Object-}
```
public final void setData(Object value)
```


QR-Code 콘텐츠에 직렬화할 사용자 정의 객체를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

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


문서 페이지에 삽입된 서명의 QR-Code 이미지 콘텐츠를 가져오기 위한 플래그를 가져오거나 설정합니다.
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


문서 페이지에 삽입된 서명의 QR-Code 이미지 콘텐츠를 가져오기 위한 플래그를 가져오거나 설정합니다.
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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 QR-Code 이미지 콘텐츠가 .png 형식으로 반환됩니다.


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
([QrCodeSignature.getFormat](../../com.groupdocs.signature.domain.signatures/qrcodesignature#getFormat)/{@link QrCodeSignature#(FileType)})
가능한 지원 값은 다음과 같습니다: FileType.JPEG, FileType.PNG, FileType.BMP.
제공된 형식이 지원되지 않으면 QR-Code 이미지 콘텐츠가 .png 형식으로 반환됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
### signature() {#signature--}
```
public BaseSignature signature()
```




**Returns:**
[BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
