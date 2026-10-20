---
title: "DigitalSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "디지털 서명 속성을 포함합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.domain.signatures/digitalsignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public class DigitalSignature extends BaseSignature
```

디지털 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalSignature()](#DigitalSignature--) | 기본 매개변수로 Digital 서명을 초기화합니다. |
|
|  | [DigitalSignature(String signatureId)](#DigitalSignature-java.lang.String-) | 알려진 SignatureId로 Digital 서명을 초기화합니다. |
|
|  | [DigitalSignature(KeyStore certificate)](#DigitalSignature-java.security.KeyStore-) | 지정된 인증서로 Digital 서명을 생성합니다. |
|
|  | [DigitalSignature(X509Certificate cert, PrivateKey key)](#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-) | X509Certificate 인증서와 PrivateKey를 기반으로 디지털 서명을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getCertificate()](#getCertificate--) | KeyStore 인증서를 가져오거나 설정합니다. |
|
|  | [setCertificate(KeyStore value)](#setCertificate-java.security.KeyStore-) | KeyStore 인증서를 가져오거나 설정합니다. |
|
|  | [getX509Certificate()](#getX509Certificate--) | X509 인증서를 가져오거나 설정합니다. |
|
|  | [setX509Certificate(X509Certificate value)](#setX509Certificate-java.security.cert.X509Certificate-) | X509 인증서를 가져오거나 설정합니다. |
|
|  | [getPrivateKey()](#getPrivateKey--) | 인증서의 PrivateKey를 가져오거나 설정합니다. |
|
|  | [setPrivateKey(PrivateKey value)](#setPrivateKey-java.security.PrivateKey-) | 인증서의 PrivateKey를 가져오거나 설정합니다. |
|
|  | [getCertificateName()](#getCertificateName--) | X509 인증서 이름을 가져오거나 설정합니다. |
|
|  | [setCertificateName(String value)](#setCertificateName-java.lang.String-) | X509 인증서 이름을 가져오거나 설정합니다. |
|
|  | [getComments()](#getComments--) | 서명 목적 주석을 가져오거나 설정합니다. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 서명 목적 주석을 가져오거나 설정합니다. |
|
|  | [isValid()](#isValid--) | 디지털 서명이 유효하고 문서가 변조되지 않은 경우 true를 유지합니다. |
|
|  | [setValid(boolean value)](#setValid-boolean-) | 디지털 서명이 유효하고 문서가 변조되지 않은 경우 true를 유지합니다. |
|
|  | [getSignTime()](#getSignTime--) | 문서가 서명된 시간을 가져오거나 설정합니다. |
|
|  | [setSignTime(Date value)](#setSignTime-java.util.Date-) | 문서가 서명된 시간을 가져오거나 설정합니다. |
|
|  | [getXAdESType()](#getXAdESType--) | XAdES 유형 |
XAdESType
.
|
|  | [setXAdESType(int value)](#setXAdESType-int-) | XAdES 유형 |
XAdESType
.
|
|  | [getThumbprint()](#getThumbprint--) | 인증서의 지문을 가져옵니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Barcode Signature 인스턴스를 복제합니다. |
|
|  | [loadDigitalSignatures()](#loadDigitalSignatures--) | 시스템의 모든 X509 인증서 저장소에서 디지털 서명을 로드합니다. |
|
|  | [loadDigitalSignatures(StoreName storeName)](#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-) | 전달된 X509 인증서 저장소에서 디지털 서명을 로드합니다. |
|
### DigitalSignature() {#DigitalSignature--}
```
public DigitalSignature()
```


기본 매개변수로 Digital 서명을 초기화합니다.


### DigitalSignature(String signatureId) {#DigitalSignature-java.lang.String-}
```
public DigitalSignature(String signatureId)
```


알려진 SignatureId로 Digital 서명을 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signatureId | java.lang.String |  |

### DigitalSignature(KeyStore certificate) {#DigitalSignature-java.security.KeyStore-}
```
public DigitalSignature(KeyStore certificate)
```


지정된 인증서로 Digital 서명을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 인증서 | java.security.KeyStore | X509 인증서. |
|

### DigitalSignature(X509Certificate cert, PrivateKey key) {#DigitalSignature-java.security.cert.X509Certificate-java.security.PrivateKey-}
```
public DigitalSignature(X509Certificate cert, PrivateKey key)
```


X509Certificate 인증서와 PrivateKey를 기반으로 디지털 서명을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | cert | java.security.cert.X509Certificate | X509Certificate 인증서. |
|
|  | key | java.security.PrivateKey | 인증서의 PrivateKey. |
|

### getCertificate() {#getCertificate--}
```
public final KeyStore getCertificate()
```


KeyStore 인증서를 가져오거나 설정합니다.


**Returns:**
java.security.KeyStore
### setCertificate(KeyStore value) {#setCertificate-java.security.KeyStore-}
```
public final void setCertificate(KeyStore value)
```


KeyStore 인증서를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.security.KeyStore |  |

### getX509Certificate() {#getX509Certificate--}
```
public final X509Certificate getX509Certificate()
```


X509 인증서를 가져오거나 설정합니다.


**Returns:**
java.security.cert.X509Certificate
### setX509Certificate(X509Certificate value) {#setX509Certificate-java.security.cert.X509Certificate-}
```
public final void setX509Certificate(X509Certificate value)
```


X509 인증서를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.security.cert.X509Certificate |  |

### getPrivateKey() {#getPrivateKey--}
```
public final PrivateKey getPrivateKey()
```


인증서의 PrivateKey를 가져오거나 설정합니다.


**Returns:**
java.security.PrivateKey
### setPrivateKey(PrivateKey value) {#setPrivateKey-java.security.PrivateKey-}
```
public final void setPrivateKey(PrivateKey value)
```


인증서의 PrivateKey를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.security.PrivateKey |  |

### getCertificateName() {#getCertificateName--}
```
public final String getCertificateName()
```


X509 인증서 이름을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setCertificateName(String value) {#setCertificateName-java.lang.String-}
```
public final void setCertificateName(String value)
```


X509 인증서 이름을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


서명 목적 주석을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


서명 목적 주석을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### isValid() {#isValid--}
```
public final boolean isValid()
```


디지털 서명이 유효하고 문서가 변조되지 않은 경우 true를 유지합니다.


**Returns:**
boolean
### setValid(boolean value) {#setValid-boolean-}
```
public final void setValid(boolean value)
```


디지털 서명이 유효하고 문서가 변조되지 않은 경우 true를 유지합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getSignTime() {#getSignTime--}
```
public final Date getSignTime()
```


문서가 서명된 시간을 가져오거나 설정합니다.


**Returns:**
java.util.Date
### setSignTime(Date value) {#setSignTime-java.util.Date-}
```
public final void setSignTime(Date value)
```


문서가 서명된 시간을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.Date |  |

### getXAdESType() {#getXAdESType--}
```
public final int getXAdESType()
```


XAdES 유형
XAdESType
. 기본값은 None이며 (XAdES가 비활성화됩니다).
현재 XAdES 서명 유형은 스프레드시트 문서에서만 지원됩니다.


**Returns:**
int
### setXAdESType(int value) {#setXAdESType-int-}
```
public final void setXAdESType(int value)
```


XAdES 유형
XAdESType
. 기본값은 None이며 (XAdES가 비활성화됩니다).
현재 XAdES 서명 유형은 스프레드시트 문서에서만 지원됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


인증서의 지문을 가져옵니다.


**Returns:**
java.lang.String
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

### loadDigitalSignatures() {#loadDigitalSignatures--}
```
public static List<DigitalSignature> loadDigitalSignatures()
```


시스템의 모든 X509 인증서 저장소에서 디지털 서명을 로드합니다.


**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) 디지털 서명의 목록을 반환합니다.

### loadDigitalSignatures(StoreName storeName) {#loadDigitalSignatures-com.groupdocs.signature.domain.signatures.StoreName-}
```
public static List<DigitalSignature> loadDigitalSignatures(StoreName storeName)
```


전달된 X509 인증서 저장소에서 디지털 서명을 로드합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| storeName | [StoreName](../../com.groupdocs.signature.domain.signatures/storename) |  |

**Returns:**
java.util.List<com.groupdocs.signature.domain.signatures.DigitalSignature> - [DigitalSignature](../../com.groupdocs.signature.domain.signatures/digitalsignature) 디지털 서명의 목록을 반환합니다.

