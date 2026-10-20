---
title: "QrCodeVerifyOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 QR 코드 서명을 검증하기 위한 옵션을 유지합니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.verify/qrcodeverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions), [com.groupdocs.signature.options.verify.TextVerifyOptions](../../com.groupdocs.signature.options.verify/textverifyoptions)
```
public class QrCodeVerifyOptions extends TextVerifyOptions
```

문서 QR 코드 서명을 검증하기 위한 옵션을 유지합니다.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for QR-code electronic signature by GroupDocs.Signature: [How to eVerification QR-code signatures in a document](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures-in-the-document/)
* Advanced usage of settings of verification for QR-code electronic signature with GroupDocs.Signature: [Advanced usage of eVerification QR-code signatures in a document and additional settings](../https://docs.groupdocs.com/signature/java/verify-qr-code-signatures/)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [QrCodeVerifyOptions()](#QrCodeVerifyOptions--) | QR-Code 서명을 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다. |
|
|  | [QrCodeVerifyOptions(String text)](#QrCodeVerifyOptions-java.lang.String-) | 검증 텍스트가 포함된 QR-Code 서명을 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다. |
|
|  | [QrCodeVerifyOptions(String text, QrCodeType encodeType)](#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | 텍스트와 QR 코드 인코드 유형을 사용하여 QR 코드 서명을 검증하기 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getEncodeType()](#getEncodeType--) | QR 코드 유형 검증을 가져오거나 설정합니다. |
|
|  | [setEncodeType(QrCodeType value)](#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-) | QR 코드 유형 검증을 가져오거나 설정합니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR 코드 서명 텍스트 속성을 인코딩 및 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR 코드 서명 텍스트 속성을 인코딩 및 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### QrCodeVerifyOptions() {#QrCodeVerifyOptions--}
```
public QrCodeVerifyOptions()
```


QR-Code 서명을 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다.


### QrCodeVerifyOptions(String text) {#QrCodeVerifyOptions-java.lang.String-}
```
public QrCodeVerifyOptions(String text)
```


검증 텍스트가 포함된 QR-Code 서명을 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 검증할 QR 코드 텍스트 |
|

### QrCodeVerifyOptions(String text, QrCodeType encodeType) {#QrCodeVerifyOptions-java.lang.String-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public QrCodeVerifyOptions(String text, QrCodeType encodeType)
```


텍스트와 QR 코드 인코드 유형을 사용하여 QR 코드 서명을 검증하기 위한 QRCodeVerifyOptions 검증 옵션을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 텍스트 | java.lang.String | 검증할 텍스트 |
|
|  | encodeType | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) | 인코딩 유형 |
|

### getEncodeType() {#getEncodeType--}
```
public final QrCodeType getEncodeType()
```


QR 코드 유형 검증을 가져오거나 설정합니다. 이 속성은 선택 사항입니다.


**Returns:**
[QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype)
### setEncodeType(QrCodeType value) {#setEncodeType-com.groupdocs.signature.domain.qrcodes.QrCodeType-}
```
public final void setEncodeType(QrCodeType value)
```


QR 코드 유형 검증을 가져오거나 설정합니다. 이 속성은 선택 사항입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [QrCodeType](../../com.groupdocs.signature.domain.qrcodes/qrcodetype) |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR 코드 서명 텍스트 속성을 인코딩 및 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR 코드 서명 텍스트 속성을 인코딩 및 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
