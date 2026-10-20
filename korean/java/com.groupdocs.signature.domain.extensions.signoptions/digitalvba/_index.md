---
title: "DigitalVBA"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스프레드시트 VBA 프로젝트용 디지털 서명을 나타냅니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.domain.extensions.signoptions/digitalvba/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.extensions.signoptions.SignatureExtension](../../com.groupdocs.signature.domain.extensions.signoptions/signatureextension)
```
public class DigitalVBA extends SignatureExtension
```

스프레드시트 VBA 프로젝트용 디지털 서명을 나타냅니다.
Xlsm 또는 Xltm과 같은 특정 스프레드시트 문서 형식에서 VBA 프로젝트에 서명할 수 있는 기능을 제공합니다.
여러 DigitalVBA 확장이 DigitalSignOptions.Extensions에 추가된 경우, 첫 번째만 문서 서명에 사용됩니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [DigitalVBA(String certificateFilePath, String password)](#DigitalVBA-java.lang.String-java.lang.String-) | 인증서 파일을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [DigitalVBA(InputStream certificateStream, String password)](#DigitalVBA-java.io.InputStream-java.lang.String-) | 인증서 스트림을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getComments()](#getComments--) | 서명 주석을 가져오거나 설정합니다. |
|
|  | [setComments(String value)](#setComments-java.lang.String-) | 서명 주석을 가져오거나 설정합니다. |
|
|  | [getPassword()](#getPassword--) | 디지털 인증서의 비밀번호를 가져오거나 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 디지털 인증서의 비밀번호를 가져오거나 설정합니다. |
|
|  | [getSignOnlyVBAProject()](#getSignOnlyVBAProject--) | VBA 프로젝트 서명만 설정을 가져오거나 설정합니다. |
|
|  | [setSignOnlyVBAProject(boolean value)](#setSignOnlyVBAProject-boolean-) | VBA 프로젝트 서명만 설정을 가져오거나 설정합니다. |
|
|  | [getCertificateFilePath()](#getCertificateFilePath--) | 디지털 인증서 파일 경로를 가져옵니다. |
|
|  | [getCertificateStream()](#getCertificateStream--) | 디지털 인증서 스트림을 가져옵니다. |
|
|  | [release()](#release--) | 서명 후 리소스를 정리하기 위해 메서드를 재정의합니다. |
|
### DigitalVBA(String certificateFilePath, String password) {#DigitalVBA-java.lang.String-java.lang.String-}
```
public DigitalVBA(String certificateFilePath, String password)
```


인증서 파일을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateFilePath | java.lang.String | 디지털 인증서 파일 경로 |
|
|  | password | java.lang.String | 디지털 인증서 비밀번호 |
|

### DigitalVBA(InputStream certificateStream, String password) {#DigitalVBA-java.io.InputStream-java.lang.String-}
```
public DigitalVBA(InputStream certificateStream, String password)
```


인증서 스트림을 사용하여 DigitalVBA 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | certificateStream | java.io.InputStream | 디지털 인증서 스트림 |
|
|  | password | java.lang.String | 디지털 인증서 비밀번호 |
|

### getComments() {#getComments--}
```
public final String getComments()
```


서명 주석을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


서명 주석을 가져오거나 설정합니다.


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

### getSignOnlyVBAProject() {#getSignOnlyVBAProject--}
```
public final boolean getSignOnlyVBAProject()
```


VBA 프로젝트 서명만 설정을 가져오거나 설정합니다.
true로 설정하면 SpreadSheet 문서는 서명되지 않지만 VBA 프로젝트는 서명됩니다.


**Returns:**
boolean
### setSignOnlyVBAProject(boolean value) {#setSignOnlyVBAProject-boolean-}
```
public final void setSignOnlyVBAProject(boolean value)
```


VBA 프로젝트 서명만 설정을 가져오거나 설정합니다.
true로 설정하면 SpreadSheet 문서는 서명되지 않지만 VBA 프로젝트는 서명됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getCertificateFilePath() {#getCertificateFilePath--}
```
public final String getCertificateFilePath()
```


디지털 인증서 파일 경로를 가져옵니다.
이 속성은 CertificateStream이 지정되지 않은 경우에만 사용됩니다.


**Returns:**
java.lang.String
### getCertificateStream() {#getCertificateStream--}
```
public final InputStream getCertificateStream()
```


디지털 인증서 스트림을 가져옵니다.
이 속성이 지정되면 항상 CertificateFilePath 대신 사용됩니다.


**Returns:**
java.io.InputStream
### release() {#release--}
```
public void release()
```


서명 후 리소스를 정리하기 위해 메서드를 재정의합니다.


