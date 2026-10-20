---
title: "SymmetricEncryption"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "단일 키와 암호 구문 소금을 사용한 데이터 암호화를 위한 표준 대칭 알고리즘을 구현합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.extensions.encryption/symmetricencryption/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.groupdocs.signature.domain.extensions.encryption.IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
```
public final class SymmetricEncryption implements IDataEncryption
```

단일 키와 암호 구문(소금)을 사용한 데이터 암호화를 위한 표준 대칭 알고리즘을 구현합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SymmetricEncryption(int algorithmType, String key, String salt)](#SymmetricEncryption-int-java.lang.String-java.lang.String-) | 매개변수를 사용하여 대칭 암호화 알고리즘을 생성합니다. |
|
|  | [SymmetricEncryption(int algorithmType, String key)](#SymmetricEncryption-int-java.lang.String-) | 기본 암호 구문으로 대칭 암호화 알고리즘을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getAlgorithmType()](#getAlgorithmType--) | 대칭 알고리즘의 유형을 가져오거나 설정합니다. |
|
|  | [setAlgorithmType(int value)](#setAlgorithmType-int-) | 대칭 알고리즘의 유형을 가져오거나 설정합니다. |
|
|  | [getKey()](#getKey--) | 암호화 알고리즘의 키를 가져오거나 설정합니다. |
|
|  | [setKey(String value)](#setKey-java.lang.String-) | 암호화 알고리즘의 키를 가져오거나 설정합니다. |
|
|  | [getSalt()](#getSalt--) | 암호화 알고리즘의 암호 구문을 가져오거나 설정합니다. |
|
|  | [setSalt(String value)](#setSalt-java.lang.String-) | 암호화 알고리즘의 암호 구문을 가져오거나 설정합니다. |
|
|  | [encode(String source)](#encode-java.lang.String-) | 제공된 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 문자열을 암호화합니다. |
|
|  | [decode(String source)](#decode-java.lang.String-) | 제공된 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 문자열을 복호화합니다. |
|
### SymmetricEncryption(int algorithmType, String key, String salt) {#SymmetricEncryption-int-java.lang.String-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key, String salt)
```


매개변수를 사용하여 대칭 암호화 알고리즘을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | algorithmType | int | 대칭 알고리즘 유형을 지정합니다. |
|
|  | key | java.lang.String | 암호화 키 |
|
|  | 솔트 | java.lang.String | 암호화용 암호 구문 |
|

### SymmetricEncryption(int algorithmType, String key) {#SymmetricEncryption-int-java.lang.String-}
```
public SymmetricEncryption(int algorithmType, String key)
```


기본 암호 구문으로 대칭 암호화 알고리즘을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | algorithmType | int | 대칭 알고리즘 유형을 지정합니다. |
|
|  | key | java.lang.String | 암호화 키 |
|

### getAlgorithmType() {#getAlgorithmType--}
```
public final int getAlgorithmType()
```


대칭 알고리즘의 유형을 가져오거나 설정합니다.


**Returns:**
int
### setAlgorithmType(int value) {#setAlgorithmType-int-}
```
public final void setAlgorithmType(int value)
```


대칭 알고리즘의 유형을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getKey() {#getKey--}
```
public final String getKey()
```


암호화 알고리즘의 키를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


암호화 알고리즘의 키를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSalt() {#getSalt--}
```
public final String getSalt()
```


암호화 알고리즘의 암호 구문을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setSalt(String value) {#setSalt-java.lang.String-}
```
public final void setSalt(String value)
```


암호화 알고리즘의 암호 구문을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### encode(String source) {#encode-java.lang.String-}
```
public final String encode(String source)
```


제공된 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 문자열을 암호화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 소스 | java.lang.String | 인코딩할 원본 문자열. |
|

**Returns:**
java.lang.String - 암호화된 문자열을 반환합니다.

### decode(String source) {#decode-java.lang.String-}
```
public final String decode(String source)
```


제공된 알고리즘 유형, 키 및 솔트 매개변수를 기반으로 문자열을 복호화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 소스 | java.lang.String | 디코딩할 암호화된 문자열. |
|

**Returns:**
java.lang.String - 복호화된 문자열을 반환합니다.

