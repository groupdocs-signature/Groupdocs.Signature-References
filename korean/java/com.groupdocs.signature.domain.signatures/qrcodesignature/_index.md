---
title: "QrCodeSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "QR 코드 서명 속성을 포함합니다."
type: docs
weight: 16
url: /ko/java/com.groupdocs.signature.domain.signatures/qrcodesignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class QrCodeSignature extends BaseSignature
```

QR 코드 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [QrCodeSignature(String signatureId)](#QrCodeSignature-java.lang.String-) | 검색 프로세스 후에 얻은 서명 식별자를 사용하여 QrCodeSignature 객체를 초기화합니다. |
|
| [QrCodeSignature()](#QrCodeSignature--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR 코드 인코드 유형을 지정합니다. |
|
|  | [getText()](#getText--) | QR 코드의 텍스트를 지정합니다. |
|
|  | [getFormat()](#getFormat--) | QR 코드 서명 이미지의 형식을 지정합니다. |
|
|  | [getContent()](#getContent--) | QR 코드 바이너리 데이터 이미지 콘텐츠 유형을 지정합니다 |
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
|
|  | [<T>getData(Class<T> type)](#-T-getData-java.lang.Class-T--) | 역직렬화 시 QR-Code 서명 텍스트에서 객체를 가져옵니다. |
|
|  | [<T>getData(IDataEncryption dataEncryption, Class<T> type)](#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--) | 역직렬화 시 QR-Code 서명 텍스트에서 객체를 가져옵니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | QR-Code 서명 인스턴스를 복제합니다. |
|
| [setContent(SignOptions signOptions, BufferedImage image)](#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-) |  |
### QrCodeSignature(String signatureId) {#QrCodeSignature-java.lang.String-}
```
public QrCodeSignature(String signatureId)
```


검색 프로세스 후에 얻은 서명 식별자를 사용하여 QrCodeSignature 객체를 초기화합니다.
이 고유 식별자는 문서 서명 정보 레이어에서 이 서명의 추가 속성을 찾는 데 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | signatureId | java.lang.String | 서명 또는 검색 방법으로 얻은 고유 서명 식별자입니다. |
|

### QrCodeSignature() {#QrCodeSignature--}
```
public QrCodeSignature()
```


### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR 코드 인코드 유형을 지정합니다.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### getText() {#getText--}
```
public final String getText()
```


QR 코드의 텍스트를 지정합니다.


**Returns:**
java.lang.String
### getFormat() {#getFormat--}
```
public final FileType getFormat()
```


QR 코드 서명 이미지의 형식을 지정합니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### getContent() {#getContent--}
```
public final byte[] getContent()
```


QR 코드 바이너리 데이터 이미지 콘텐츠 유형을 지정합니다
Format
(#getFormat.getFormat/#setFormat(FileType).setFormat(FileType)).
기본적으로 이 속성은 설정되지 않습니다.
속성 사용
QrCodeSearchOptions.ReturnContent
([QrCodeSearchOptions.getReturnContent](../../com.groupdocs.signature.options.search/qrcodesearchoptions#getReturnContent)/[QrCodeSearchOptions.setReturnContent(boolean)](../../com.groupdocs.signature.options.search/qrcodesearchoptions#setReturnContent-boolean-)) 이 기능을 활성화하려면.


**Returns:**
byte[]
### <T>getData(Class<T> type) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> type)
```


역직렬화 시 QR-Code 서명 텍스트에서 객체를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 유형 | java.lang.Class<T> |  |

**Returns:**
T -
T
: QR-Code 텍스트에서 역직렬화할 객체 유형

### <T>getData(IDataEncryption dataEncryption, Class<T> type) {#-T-getData-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-java.lang.Class-T--}
```
public final T <T>getData(IDataEncryption dataEncryption, Class<T> type)
```


역직렬화 시 QR-Code 서명 텍스트에서 객체를 가져옵니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | 사용자 지정 데이터 암호화 구현을 설정합니다 |


T
: QR-Code 텍스트에서 역직렬화할 객체 유형
|
| 유형 | java.lang.Class<T> |  |

**Returns:**
T -
### equals(Object signature) {#equals-java.lang.Object-}
```
public boolean equals(Object signature)
```


서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 서명 | java.lang.Object | 비교할 서명 객체. |
|

**Returns:**
boolean - 전달된 서명 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - 서명 해시 코드

### deepClone() {#deepClone--}
```
public Object deepClone()
```


QR-Code 서명 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 QR-code 서명 인스턴스를 반환합니다.

### setContent(SignOptions signOptions, BufferedImage image) {#setContent-com.groupdocs.signature.options.sign.SignOptions-java.awt.image.BufferedImage-}
```
public final void setContent(SignOptions signOptions, BufferedImage image)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signOptions | [SignOptions](../../com.groupdocs.signature.options.sign/signoptions) |  |
| 이미지 | java.awt.image.BufferedImage |  |

