---
title: "DigitalVerifyOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서 디지털 서명을 검증하기 위한 옵션을 유지합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.verify/digitalverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class DigitalVerifyOptions extends VerifyOptions
```

문서 디지털 서명을 검증하기 위한 옵션을 유지합니다.

<br />

*** ** * ** ***

**Learn more**

* Basic usage of verification for Digital electronic signature by GroupDocs.Signature: [How to eVerification Digital signatures in a document](../https://docs.groupdocs.com/signature/java/verify-digital-signatures-in-the-document/)
* Advanced usage of settings of verification for Digital electronic signature with GroupDocs.Signature: [Advanced usage of eVerification Digital signatures in a document and additional settings](../)

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalVerifyOptions()](#DigitalVerifyOptions--) | 기본값으로 Digital Verification Option을 생성합니다. |
|
|  | [DigitalVerifyOptions(String certificateGuid)](#DigitalVerifyOptions-java.lang.String-) | 주어진 디지털 인증서 GUID로 Digital Verification Option을 생성합니다. |
|
|  | [DigitalVerifyOptions(InputStream certificateStream)](#DigitalVerifyOptions-java.io.InputStream-) | 주어진 인증서 스트림으로 Digital Verification Option을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | Certificate Guid 또는 스트림에서 X509Certificate2 인증서를 가져옵니다. |
|
|  | [getPassword()](#getPassword--) | 필요한 경우 Digital Certificate의 비밀번호. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 필요한 경우 Digital Certificate의 비밀번호. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | Digital Certificate의 파일 GUID. |
|
|  | [setCertificateFilePath(String value)](#setCertificateFilePath-java.lang.String-) | Digital Certificate의 파일 GUID. |
|
|  | [getCertificateStream()](#getCertificateStream--) | Digital Certificate 스트림. |
|
|  | [setCertificateStream(InputStream value)](#setCertificateStream-java.io.InputStream-) | Digital Certificate 스트림. |
|
|  | [getComments()](#getComments--) | 검증할 Digital Signature의 주석. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 검증할 Digital Signature의 주석. |
|
|  | [getSignDateTimeFrom()](#getSignDateTimeFrom--) | 검증할 Digital Signature의 날짜 및 시간 범위. |
|
|  | [setSignDateTimeFrom(Date value)](#setSignDateTimeFrom-java.util.Date-) | 검증할 Digital Signature의 날짜 및 시간 범위. |
|
|  | [getSignDateTimeTo()](#getSignDateTimeTo--) | 검증할 Digital Signature의 날짜 및 시간 범위. |
|
|  | [setSignDateTimeTo(Date value)](#setSignDateTimeTo-java.util.Date-) | 검증할 Digital Signature의 날짜 및 시간 범위. |
|
|  | [getReason()](#getReason--) | 검증할 Digital Signature의 이유. |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 검증할 Digital Signature의 이유. |
|
|  | [getContact()](#getContact--) | 검증할 Signature Contact. |
|
|  | [setContact(String value)](#setContact-java.lang.String-) | 검증할 Signature Contact. |
|
|  | [getLocation()](#getLocation--) | 검증할 Signature Location. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 검증할 Signature Location. |
|
|  | [getSubjectName()](#getSubjectName--) | 검증할 인증서의 Subject 구별 이름. |
|
|  | [setSubjectName(String value)](#setSubjectName-java.lang.String-) | 검증할 인증서의 Subject 구별 이름. |
|
|  | [getIssuerName()](#getIssuerName--) | 검증할 인증서의 Issuer 이름. |
|
|  | [setIssuerName(String value)](#setIssuerName-java.lang.String-) | 검증할 인증서의 Issuer 이름. |
|
### DigitalVerifyOptions() {#DigitalVerifyOptions--}
```
public DigitalVerifyOptions()
```


기본값으로 Digital Verification Option을 생성합니다.


### DigitalVerifyOptions(String certificateGuid) {#DigitalVerifyOptions-java.lang.String-}
```
public DigitalVerifyOptions(String certificateGuid)
```


주어진 디지털 인증서 GUID로 Digital Verification Option을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateGuid | java.lang.String | 디지털 인증서의 파일 경로. |
|

### DigitalVerifyOptions(InputStream certificateStream) {#DigitalVerifyOptions-java.io.InputStream-}
```
public DigitalVerifyOptions(InputStream certificateStream)
```


주어진 인증서 스트림으로 Digital Verification Option을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 인증서 스트림. |
|

### getCertificate() {#getCertificate--}
```
public KeyStore getCertificate()
```


Certificate Guid 또는 스트림에서 X509Certificate2 인증서를 가져옵니다.


**Returns:**
java.security.KeyStore
### getPassword() {#getPassword--}
```
public final String getPassword()
```


필요한 경우 Digital Certificate의 비밀번호.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


필요한 경우 Digital Certificate의 비밀번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


Digital Certificate의 파일 GUID.


**Returns:**
java.lang.String
### setCertificateFilePath(String value) {#setCertificateFilePath-java.lang.String-}
```
public final void setCertificateFilePath(String value)
```


Digital Certificate의 파일 GUID.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


Digital Certificate 스트림.


**Returns:**
java.io.InputStream
### setCertificateStream(InputStream value) {#setCertificateStream-java.io.InputStream-}
```
public final void setCertificateStream(InputStream value)
```


Digital Certificate 스트림.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.io.InputStream |  |

### getComments() {#getComments--}
```
public final String getComments()
```


검증할 Digital Signature의 주석.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


검증할 Digital Signature의 주석.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSignDateTimeFrom() {#getSignDateTimeFrom--}
```
public Date getSignDateTimeFrom()
```


검증할 Digital Signature의 날짜 및 시간 범위. Nullable 값은 무시됩니다.


**Returns:**
java.util.Date
### setSignDateTimeFrom(Date value) {#setSignDateTimeFrom-java.util.Date-}
```
public void setSignDateTimeFrom(Date value)
```


검증할 Digital Signature의 날짜 및 시간 범위. Nullable 값은 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getSignDateTimeTo() {#getSignDateTimeTo--}
```
public Date getSignDateTimeTo()
```


검증할 Digital Signature의 날짜 및 시간 범위. Nullable 값은 무시됩니다.


**Returns:**
java.util.Date
### setSignDateTimeTo(Date value) {#setSignDateTimeTo-java.util.Date-}
```
public void setSignDateTimeTo(Date value)
```


검증할 Digital Signature의 날짜 및 시간 범위. Nullable 값은 무시됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getReason() {#getReason--}
```
public final String getReason()
```


검증할 Digital Signature의 이유.


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


검증할 Digital Signature의 이유.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getContact() {#getContact--}
```
public final String getContact()
```


검증할 Signature Contact.


**Returns:**
java.lang.String
### setContact(String value) {#setContact-java.lang.String-}
```
public final void setContact(String value)
```


검증할 Signature Contact.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


검증할 Signature Location.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


검증할 Signature Location.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSubjectName() {#getSubjectName--}
```
public final String getSubjectName()
```


검증할 인증서의 Subject 구별 이름. 값은 대소문자를 구분합니다.
이 속성이 설정되면 검증은 Signature subject name이 전달된 값을 포함하거나 동일한지 확인합니다.


**Returns:**
java.lang.String
### setSubjectName(String value) {#setSubjectName-java.lang.String-}
```
public final void setSubjectName(String value)
```


검증할 인증서의 Subject 구별 이름. 값은 대소문자를 구분합니다.
이 속성이 설정되면 검증은 Signature subject name이 전달된 값을 포함하거나 동일한지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getIssuerName() {#getIssuerName--}
```
public final String getIssuerName()
```


검증할 인증서의 발급자 이름. 값은 대소문자를 구분합니다.
이 속성이 설정되면 검증은 서명의 발급자 이름이 전달된 값을 포함하거나 동일한지 확인합니다.


**Returns:**
java.lang.String
### setIssuerName(String value) {#setIssuerName-java.lang.String-}
```
public final void setIssuerName(String value)
```


검증할 인증서의 발급자 이름. 값은 대소문자를 구분합니다.
이 속성이 설정되면 검증은 서명의 발급자 이름이 전달된 값을 포함하거나 동일한지 확인합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

