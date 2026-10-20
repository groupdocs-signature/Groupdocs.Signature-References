---
title: "DigitalSignOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "디지털 서명 옵션을 나타냅니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.sign/digitalsignoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.sign.SignOptions](../../com.groupdocs.signature.options.sign/signoptions), [com.groupdocs.signature.options.sign.ImageSignOptions](../../com.groupdocs.signature.options.sign/imagesignoptions)
```
public class DigitalSignOptions extends ImageSignOptions
```

디지털 서명 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalSignOptions()](#DigitalSignOptions--) | DigitalSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [DigitalSignOptions(String certificateFilePath)](#DigitalSignOptions-java.lang.String-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일로 초기화합니다. |
|
|  | [DigitalSignOptions(InputStream certificateStream)](#DigitalSignOptions-java.io.InputStream-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림으로 초기화합니다. |
|
|  | [DigitalSignOptions(String certificateFilePath, String imageFilePath)](#DigitalSignOptions-java.lang.String-java.lang.String-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일 및 이미지 파일로 초기화합니다. |
|
|  | [DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)](#DigitalSignOptions-java.lang.String-java.io.InputStream-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일 및 이미지 스트림으로 초기화합니다. |
|
|  | [DigitalSignOptions(InputStream certificateStream, String imageFilePath)](#DigitalSignOptions-java.io.InputStream-java.lang.String-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림 및 이미지 파일로 초기화합니다. |
|
|  | [DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)](#DigitalSignOptions-java.io.InputStream-java.io.InputStream-) | DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림 및 이미지 스트림으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getReason()](#getReason--) | 서명의 이유를 가져오거나 설정합니다. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 서명의 이유를 가져오거나 설정합니다. |
|
|  | [getContact()](#getContact--) | 서명 연락처를 가져오거나 설정합니다. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 서명 연락처를 가져오거나 설정합니다. |
|
|  | [getLocation()](#getLocation--) | 서명 위치를 가져오거나 설정합니다. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 서명 위치를 가져오거나 설정합니다. |
|
|  | [getPassword()](#getPassword--) | 디지털 인증서의 비밀번호를 가져오거나 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 디지털 인증서의 비밀번호를 가져오거나 설정합니다. |
|
|  | [getSignature()](#getSignature--) | 문서 디지털 서명의 속성을 가져오거나 설정합니다. |
|
|  | [setSignature(DigitalSignature value)](#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-) | 문서 디지털 서명의 속성을 가져오거나 설정합니다. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | 디지털 인증서 파일 경로를 가져오거나 설정합니다. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | 디지털 인증서 파일 GUID를 가져오거나 설정합니다. |
|
|  | [getCertificateStream()](#getCertificateStream--) | 디지털 인증서 스트림을 가져오거나 설정합니다. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | 디지털 인증서 스트림을 가져오거나 설정합니다. |
|
|  | [getVisible()](#getVisible--) | 서명의 가시성을 가져오거나 설정합니다. |
|
|  | [setVisible(boolean value)](#setVisible-boolean-) | 서명의 가시성을 가져오거나 설정합니다. |
|
|  | [getUseLtv()](#getUseLtv--) | LTV (Long Term Validation) 검증 플래그를 가져오거나 설정합니다. |
|
|  | [setUseLtv(boolean value)](#setUseLtv-boolean-) | LTV (Long Term Validation) 검증 플래그를 가져오거나 설정합니다. |
|
|  | [getAllowExpired()](#getAllowExpired--) | 유효 기간이 종료된 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. |
|
|  | [setAllowExpired(boolean value)](#setAllowExpired-boolean-) | 유효 기간이 종료된 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. |
|
|  | [getAllowNotYetValid()](#getAllowNotYetValid--) | 유효 기간이 아직 시작되지 않은 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. |
|
|  | [setAllowNotYetValid(boolean value)](#setAllowNotYetValid-boolean-) | 유효 기간이 아직 시작되지 않은 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다. |
|
|  | [getCustomSignHash()](#getCustomSignHash--) | 사용자가 자체 구현을 연결할 수 있도록 사용자 지정 해시 서명 구현을 가져오거나 설정합니다. |
디지털 서명 로직(HSM, 원격 서명자, 소프트웨어 키스토어 등).
|
|  | [setCustomSignHash(ICustomSignHash value)](#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-) | 사용자가 자체 구현을 연결할 수 있도록 사용자 지정 해시 서명 구현을 설정합니다. |
디지털 서명 로직.
|
|  | [getXAdESType()](#getXAdESType--) | XAdES 유형 |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES 유형 |
XAdESType
.
|
| [getSignatureLineId()](#getSignatureLineId--) |  |
| [setSignatureLineId(UUID value)](#setSignatureLineId-java.util.UUID-) |  |
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### DigitalSignOptions() {#DigitalSignOptions--}
```
public DigitalSignOptions()
```


DigitalSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### DigitalSignOptions(String certificateFilePath) {#DigitalSignOptions-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 디지털 인증서 파일 경로 |
|

### DigitalSignOptions(InputStream certificateStream) {#DigitalSignOptions-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 디지털 인증서 스트림 |
|

### DigitalSignOptions(String certificateFilePath, String imageFilePath) {#DigitalSignOptions-java.lang.String-java.lang.String-}
```
public DigitalSignOptions(String certificateFilePath, String imageFilePath)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일 및 이미지 파일로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 디지털 인증서 파일 경로 |
|
|  | imageFilePath | java.lang.String | 서명 모양 이미지 파일 경로 |
|

### DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream) {#DigitalSignOptions-java.lang.String-java.io.InputStream-}
```
public DigitalSignOptions(String certificateFilePath, InputStream appearenceImageStream)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 파일 및 이미지 스트림으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 디지털 인증서 파일 경로 |
|
|  | appearenceImageStream | java.io.InputStream | 서명 모양 이미지 스트림 |
|

### DigitalSignOptions(InputStream certificateStream, String imageFilePath) {#DigitalSignOptions-java.io.InputStream-java.lang.String-}
```
public DigitalSignOptions(InputStream certificateStream, String imageFilePath)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림 및 이미지 파일로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 디지털 인증서 스트림 |
|
|  | imageFilePath | java.lang.String | 서명 모양 이미지 파일 경로 |
|

### DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream) {#DigitalSignOptions-java.io.InputStream-java.io.InputStream-}
```
public DigitalSignOptions(InputStream certificateStream, InputStream appearenceImageStream)
```


DigitalSignOptions 클래스의 새 인스턴스를 인증서 스트림 및 이미지 스트림으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 디지털 인증서 스트림 |
|
|  | appearenceImageStream | java.io.InputStream | 서명 모양 이미지 스트림 |
|

### getReason() {#getReason--}
```
public final String getReason()
```


서명의 이유를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


서명의 이유를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


서명 연락처를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


서명 연락처를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


서명 위치를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


서명 위치를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


디지털 인증서의 비밀번호를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


디지털 인증서의 비밀번호를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSignature() {#getSignature--}
```
public final DigitalSignature getSignature()
```


문서 디지털 서명의 속성을 가져오거나 설정합니다.


**Returns:**
[DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
### setSignature(DigitalSignature value) {#setSignature-com.groupdocs.signature.domain.signatures.DigitalSignature-}
```
public final void setSignature(DigitalSignature value)
```


문서 디지털 서명의 속성을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


디지털 인증서 파일 경로를 가져오거나 설정합니다.
이 속성은 CertificateStream이 지정되지 않은 경우에만 사용됩니다.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public void setCertificateFilePath(String value)
```


디지털 인증서 파일 GUID를 가져오거나 설정합니다.
이 속성은 CertificateStream이 지정되지 않은 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


디지털 인증서 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 CertificateGuid 대신 사용됩니다.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


디지털 인증서 스트림을 가져오거나 설정합니다.
이 속성이 지정되면 항상 CertificateGuid 대신 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

### getVisible() {#getVisible--}
```
public final boolean getVisible()
```


서명의 가시성을 가져오거나 설정합니다.


**Returns:**
boolean
### setVisible(boolean value) {#setVisible-boolean-}
```
public final void setVisible(boolean value)
```


서명의 가시성을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getUseLtv() {#getUseLtv--}
```
public final boolean getUseLtv()
```


LTV (Long Term Validation) 검증 플래그를 가져오거나 설정합니다.


**Returns:**
boolean
### setUseLtv(boolean value) {#setUseLtv-boolean-}
```
public final void setUseLtv(boolean value)
```


LTV (Long Term Validation) 검증 플래그를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAllowExpired() {#getAllowExpired--}
```
public final boolean getAllowExpired()
```


유효 기간이 종료된 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다.
기본값은 false이며, 만료된 인증서로 서명하면 예외가 발생합니다.
GroupDocsSignatureException
,
그리고 문서가 서명되지 않았습니다.


검증자는 만료된 인증서로 만든 서명이 유효하지 않다고 보고합니다. 이 속성을 true로 설정하는 경우는
예를 들어 오래된 인증서로 테스트하기 위해서라도 해당 서명이 필요합니다. 그러면 문서가 서명되고, 그리고
경고가 설정된 로거에 기록됩니다
SignatureSettings
.


인증서는 현재 UTC 시간과 비교되며, 다음과는 비교되지 않습니다
DigitalSignature.SignTime
. 플래그
다음에서 제공된 인증서에 적용됩니다
CertificateFilePath
,
CertificateStream
또는
Signature
,
그리고 스프레드시트가 서명될 때, 첫 번째
DigitalVBA
확장자. Digital
이미지 서명은 인증서를 사용하지 않으며 검증되지 않습니다. 유효 기간이 아직 시작되지 않은 인증서는
아직 시작되지 않았으며, 다음에 의해 제어됩니다
AllowNotYetValid
.


**Returns:**
boolean
### setAllowExpired(boolean value) {#setAllowExpired-boolean-}
```
public final void setAllowExpired(boolean value)
```


유효 기간이 종료된 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다.
기본값은 false입니다. #getAllowExpired().getAllowExpired()를 참조하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAllowNotYetValid() {#getAllowNotYetValid--}
```
public final boolean getAllowNotYetValid()
```


유효 기간이 아직 시작되지 않은 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다.
기본값은 false이며, 이러한 인증서로 서명하면 예외가 발생합니다
GroupDocsSignatureException
,
그리고 문서가 서명되지 않았습니다.


검증자는 인증서가 유효해지기 전에 만든 서명이 유효하지 않다고 보고합니다. 이러한 인증서는
보통 나중 날짜에 발급되었거나 컴퓨터 시계가 잘못되었습니다. 이 속성이 true이면 문서는
서명되며, 설정된 로거에 경고가 기록됩니다
SignatureSettings
.


인증서는 현재 UTC 시간과 비교됩니다. 플래그는 동일한 인증서에 적용됩니다

AllowExpired
, 인증서의 유효 기간이 끝난 경우를 제어합니다.


**Returns:**
boolean
### setAllowNotYetValid(boolean value) {#setAllowNotYetValid-boolean-}
```
public final void setAllowNotYetValid(boolean value)
```


유효 기간이 아직 시작되지 않은 인증서로 서명할 수 있게 하는 플래그를 가져오거나 설정합니다.
기본값은 false입니다. #getAllowNotYetValid().getAllowNotYetValid()를 참조하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getCustomSignHash() {#getCustomSignHash--}
```
public final ICustomSignHash getCustomSignHash()
```


사용자가 자체 구현을 연결할 수 있도록 사용자 지정 해시 서명 구현을 가져오거나 설정합니다.
디지털 서명 로직(HSM, 원격 서명자, 소프트웨어 키스토어 등).


**Returns:**
[ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash)
### setCustomSignHash(ICustomSignHash value) {#setCustomSignHash-com.groupdocs.signature.options.sign.signhash.ICustomSignHash-}
```
public final void setCustomSignHash(ICustomSignHash value)
```


사용자가 자체 구현을 연결할 수 있도록 사용자 지정 해시 서명 구현을 설정합니다.
디지털 서명 로직.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ICustomSignHash](../../com.groupdocs.signature.options.sign.signhash/icustomsignhash) |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES 유형
XAdESType
. 기본값은 None이며 (XAdES가 비활성화됩니다).
현재 XAdES 서명 유형은 .NET Framework에서만 Spreadsheet 문서에 대해 지원됩니다(.NET Standard에서는 지원되지 않음).


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES 유형
XAdESType
. 기본값은 None이며 (XAdES가 비활성화됩니다).
현재 XAdES 서명 유형은 .NET Framework에서만 Spreadsheet 문서에 대해 지원됩니다(.NET Standard에서는 지원되지 않음).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSignatureLineId() {#getSignatureLineId--}
```
public final UUID getSignatureLineId()
```




**Returns:**
java.util.UUID
### setSignatureLineId(UUID value) {#setSignatureLineId-java.util.UUID-}
```
public final void setSignatureLineId(UUID value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.UUID |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
