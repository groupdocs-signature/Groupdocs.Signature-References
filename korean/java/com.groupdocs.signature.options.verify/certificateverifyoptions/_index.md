---
title: "CertificateVerifyOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "인증서 문서를 검증하기 위한 옵션을 유지합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.verify/certificateverifyoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.verify.VerifyOptions](../../com.groupdocs.signature.options.verify/verifyoptions)
```
public class CertificateVerifyOptions extends VerifyOptions
```

인증서 문서를 검증하기 위한 옵션을 유지합니다.

<br />

*** ** * ** ***

 **Learn more** 

* 

<br />


## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [CertificateVerifyOptions()](#CertificateVerifyOptions--) | TextVerifyOptions의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [CertificateVerifyOptions(String subject)](#CertificateVerifyOptions-java.lang.String-) | 검증할 주체와 함께 CertificateVerifyOptions의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getIssuer()](#getIssuer--) | 검증이 필요하면 인증서 발급자를 지정하십시오. |
|
|  | [setIssuer(String value)](#setIssuer-java.lang.String-) | 검증이 필요하면 인증서 발급자를 지정하십시오. |
|
|  | [getSerialNumber()](#getSerialNumber--) | 검증이 필요하면 인증서 일련 번호를 지정하십시오. |
|
|  | [setSerialNumber(String value)](#setSerialNumber-java.lang.String-) | 검증이 필요하면 인증서 일련 번호를 지정하십시오. |
|
|  | [getSubject()](#getSubject--) | 검증이 필요하면 인증서 주체를 지정하십시오. |
|
|  | [setSubject(String value)](#setSubject-java.lang.String-) | 검증이 필요하면 인증서 주체를 지정하십시오. |
|
|  | [getThumbprint()](#getThumbprint--) | 검증이 필요하면 인증서 지문을 지정하십시오. |
|
|  | [setThumbprint(String value)](#setThumbprint-java.lang.String-) | 검증이 필요하면 인증서 지문을 지정하십시오. |
|
|  | [getMatchType()](#getMatchType--) | 텍스트 일치 유형 검증을 가져오거나 설정합니다. |
|
|  | [setMatchType(int value)](#setMatchType-int-) | 텍스트 일치 유형 검증을 가져오거나 설정합니다. |
|
|  | [getExpired()](#getExpired--) | 검증 결과에 따라 인증서가 만료되었는지 여부를 나타냅니다. |
|
|  | [setExpired(boolean value)](#setExpired-boolean-) | 검증 결과에 따라 인증서가 만료되었는지 여부를 나타냅니다. |
|
|  | [getPerformChainValidation()](#getPerformChainValidation--) | 검증 프로세스가 기본 검증 정책을 사용하여 X.509 체인 검증을 제공해야 하는지 여부를 가져오거나 설정합니다. |
|
|  | [setPerformChainValidation(boolean value)](#setPerformChainValidation-boolean-) | 검증 프로세스가 기본 검증 정책을 사용하여 X.509 체인 검증을 제공해야 하는지 여부를 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### CertificateVerifyOptions() {#CertificateVerifyOptions--}
```
public CertificateVerifyOptions()
```


TextVerifyOptions의 새 인스턴스를 기본값으로 초기화합니다.


### CertificateVerifyOptions(String subject) {#CertificateVerifyOptions-java.lang.String-}
```
public CertificateVerifyOptions(String subject)
```


검증할 주체와 함께 CertificateVerifyOptions의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | subject | java.lang.String | 검증할 주체 |
|

### getIssuer() {#getIssuer--}
```
public final String getIssuer()
```


검증이 필요하면 인증서 발급자를 지정하십시오.


**Returns:**
java.lang.String
### setIssuer(String value) {#setIssuer-java.lang.String-}
```
public final void setIssuer(String value)
```


검증이 필요하면 인증서 발급자를 지정하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSerialNumber() {#getSerialNumber--}
```
public final String getSerialNumber()
```


검증이 필요하면 인증서 일련 번호를 지정하십시오.


**Returns:**
java.lang.String
### setSerialNumber(String value) {#setSerialNumber-java.lang.String-}
```
public final void setSerialNumber(String value)
```


검증이 필요하면 인증서 일련 번호를 지정하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


검증이 필요하면 인증서 주체를 지정하십시오.


**Returns:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


검증이 필요하면 인증서 주체를 지정하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getThumbprint() {#getThumbprint--}
```
public final String getThumbprint()
```


검증이 필요하면 인증서 지문을 지정하십시오.


**Returns:**
java.lang.String
### setThumbprint(String value) {#setThumbprint-java.lang.String-}
```
public final void setThumbprint(String value)
```


검증이 필요하면 인증서 지문을 지정하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getMatchType() {#getMatchType--}
```
public final int getMatchType()
```


텍스트 일치 유형 검증을 가져오거나 설정합니다.


**Returns:**
int
### setMatchType(int value) {#setMatchType-int-}
```
public final void setMatchType(int value)
```


텍스트 일치 유형 검증을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getExpired() {#getExpired--}
```
public final boolean getExpired()
```


검증 결과에 따라 인증서가 만료되었는지 여부를 나타냅니다.
속성은 읽기 전용입니다.


**Returns:**
boolean
### setExpired(boolean value) {#setExpired-boolean-}
```
public final void setExpired(boolean value)
```


검증 결과에 따라 인증서가 만료되었는지 여부를 나타냅니다.
속성은 읽기 전용입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPerformChainValidation() {#getPerformChainValidation--}
```
public final boolean getPerformChainValidation()
```


검증 프로세스가 기본 검증 정책을 사용하여 X.509 체인 검증을 제공해야 하는지 여부를 가져오거나 설정합니다.
기본값은 true입니다.


**Returns:**
boolean
### setPerformChainValidation(boolean value) {#setPerformChainValidation-boolean-}
```
public final void setPerformChainValidation(boolean value)
```


검증 프로세스가 기본 검증 정책을 사용하여 X.509 체인 검증을 제공해야 하는지 여부를 가져오거나 설정합니다.
기본값은 true입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
