---
title: "PdfDigitalSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 디지털 서명 속성을 포함합니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.domain.signatures/pdfdigitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature)
```
public class PdfDigitalSignature extends DigitalSignature
```

PDF 디지털 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfDigitalSignature()](#PdfDigitalSignature--) | 인증서 없이 Pdf Digital Signature를 초기화합니다. |
|
|  | [PdfDigitalSignature(KeyStore certificate)](#PdfDigitalSignature-java.security.KeyStore-) | 지정된 인증서로 Pdf Digital signature를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getContactInfo()](#getContactInfo--) | 수신자가 서명자에게 연락할 수 있도록 서명자가 제공하는 정보 |
서명을 검증하기 위해, 예를 들어
|
|  | [setContactInfo(String value)](#setContactInfo-java.lang.String-) | 수신자가 서명자에게 연락할 수 있도록 서명자가 제공하는 정보 |
서명을 검증하기 위해, 예를 들어
|
|  | [getLocation()](#getLocation--) | 서명 시의 CPU 호스트 이름 또는 물리적 위치. |
|
|  | [setLocation(String value)](#setLocation-java.lang.String-) | 서명 시의 CPU 호스트 이름 또는 물리적 위치. |
|
|  | [getReason()](#getReason--) | 서명 이유, 예를 들어 (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [setReason(String value)](#setReason-java.lang.String-) | 서명 이유, 예를 들어 (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦). |
|
|  | [getType()](#getType--) | Pdf digital signature의 유형. |
|
|  | [setType(int value)](#setType-int-) | Pdf digital signature의 유형. |
|
|  | [getTimeStamp()](#getTimeStamp--) | Pdf digital signature의 타임스탬프. |
|
|  | [setTimeStamp(TimeStamp value)](#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-) | Pdf digital signature의 타임스탬프. |
|
|  | [getShowProperties()](#getShowProperties--) | 서명 속성을 표시/숨기도록 강제합니다. |
|
|  | [setShowProperties(boolean value)](#setShowProperties-boolean-) | 서명 속성을 표시/숨기도록 강제합니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Barcode Signature 인스턴스를 복제합니다. |
|
### PdfDigitalSignature() {#PdfDigitalSignature--}
```
public PdfDigitalSignature()
```


인증서 없이 Pdf Digital Signature를 초기화합니다.


### PdfDigitalSignature(KeyStore certificate) {#PdfDigitalSignature-java.security.KeyStore-}
```
public PdfDigitalSignature(KeyStore certificate)
```


지정된 인증서로 Pdf Digital signature를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 인증서 | java.security.KeyStore | X509 인증서. |
|

### getContactInfo() {#getContactInfo--}
```
public final String getContactInfo()
```


수신자가 서명자에게 연락할 수 있도록 서명자가 제공하는 정보
서명을 확인하려면, 예: 전화번호.


**Returns:**
java.lang.String
### setContactInfo(String value) {#setContactInfo-java.lang.String-}
```
public final void setContactInfo(String value)
```


수신자가 서명자에게 연락할 수 있도록 서명자가 제공하는 정보
서명을 확인하려면, 예: 전화번호.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getLocation() {#getLocation--}
```
public final String getLocation()
```


서명 시의 CPU 호스트 이름 또는 물리적 위치.


**Returns:**
java.lang.String
### setLocation(String value) {#setLocation-java.lang.String-}
```
public final void setLocation(String value)
```


서명 시의 CPU 호스트 이름 또는 물리적 위치.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getReason() {#getReason--}
```
public final String getReason()
```


서명 이유, 예를 들어 (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Returns:**
java.lang.String
### setReason(String value) {#setReason-java.lang.String-}
```
public final void setReason(String value)
```


서명 이유, 예를 들어 (I agree\\u0420\\u0406\\u0420\\u201a\\u0412¦).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getType() {#getType--}
```
public final int getType()
```


Pdf digital signature의 유형.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


Pdf digital signature의 유형.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getTimeStamp() {#getTimeStamp--}
```
public final TimeStamp getTimeStamp()
```


Pdf digital signature의 타임스탬프.
기본값은 null입니다.


**Returns:**
[TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp)
### setTimeStamp(TimeStamp value) {#setTimeStamp-com.groupdocs.signature.domain.structs.TimeStamp-}
```
public final void setTimeStamp(TimeStamp value)
```


Pdf digital signature의 타임스탬프.
기본값은 null입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TimeStamp](../../com.groupdocs.signature.domain.structs/timestamp) |  |

### getShowProperties() {#getShowProperties--}
```
public final boolean getShowProperties()
```


서명 속성을 강제로 표시/숨깁니다. ShowProperties가 true인 경우 서명
필드에 미리 정의된 표시 형식이 있습니다
디지털 서명자 {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} 날짜: {Date} 이유: {
이유
(#getReason.getReason/#setReason(String).setReason(String))}
위치: {
위치
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties는 기본적으로 true입니다.


**Returns:**
boolean
### setShowProperties(boolean value) {#setShowProperties-boolean-}
```
public final void setShowProperties(boolean value)
```


서명 속성을 강제로 표시/숨깁니다. ShowProperties가 true인 경우 서명
필드에 미리 정의된 표시 형식이 있습니다
디지털 서명자 {
ContactInfo
(#getContactInfo.getContactInfo/#setContactInfo(String).setContactInfo(String))} 날짜: {Date} 이유: {
이유
(#getReason.getReason/#setReason(String).setReason(String))}
위치: {
위치
(#getLocation.getLocation/#setLocation(String).setLocation(String))}
ShowProperties는 기본적으로 true입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

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


Barcode Signature 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 바코드 서명 인스턴스를 반환합니다.

