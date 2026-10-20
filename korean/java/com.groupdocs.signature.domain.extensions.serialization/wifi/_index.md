---
title: "WiFi"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "WiFi 네트워크 연결 세부 정보를 나타냅니다."
type: docs
weight: 20
url: /ko/java/com.groupdocs.signature.domain.extensions.serialization/wifi/
---
**Inheritance:**
java.lang.Object
```
public class WiFi
```

WiFi 네트워크 연결 세부 정보를 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WiFi()](#WiFi--) | 기본값으로 VCard 인스턴스를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getSSID()](#getSSID--) | WiFi SSID 이름을 가져오거나 설정합니다. |
|
|  | [setSSID(String value)](#setSSID-java.lang.String-) | WiFi SSID 이름을 가져오거나 설정합니다. |
|
|  | [getPassword()](#getPassword--) | WiFi 비밀번호를 가져오거나 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | WiFi 비밀번호를 가져오거나 설정합니다. |
|
|  | [getEncryption()](#getEncryption--) | WiFi 암호화를 가져오거나 설정합니다 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [setEncryption(int value)](#setEncryption-int-) | WiFi 암호화를 가져오거나 설정합니다 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype). |
|
|  | [getHidden()](#getHidden--) | WiFi가 숨겨진 SSID인지 여부를 가져오거나 설정합니다. |
|
|  | [setHidden(boolean value)](#setHidden-boolean-) | WiFi가 숨겨진 SSID인지 여부를 가져오거나 설정합니다. |
|
|  | [equals(Object obj)](#equals-java.lang.Object-) | VCard 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
### WiFi() {#WiFi--}
```
public WiFi()
```


기본값으로 VCard 인스턴스를 생성합니다.


### getSSID() {#getSSID--}
```
public final String getSSID()
```


WiFi SSID 이름을 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setSSID(String value) {#setSSID-java.lang.String-}
```
public final void setSSID(String value)
```


WiFi SSID 이름을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


WiFi 비밀번호를 가져오거나 설정합니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


WiFi 비밀번호를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getEncryption() {#getEncryption--}
```
public final int getEncryption()
```


WiFi 암호화를 가져오거나 설정합니다 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Returns:**
int
### setEncryption(int value) {#setEncryption-int-}
```
public final void setEncryption(int value)
```


WiFi 암호화를 가져오거나 설정합니다 [WiFiEncryptionType](../../com.groupdocs.signature.domain.extensions.serialization/wifiencryptiontype).


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```


WiFi가 숨겨진 SSID인지 여부를 가져오거나 설정합니다.


**Returns:**
boolean
### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```


WiFi가 숨겨진 SSID인지 여부를 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


VCard 속성을 비교하기 위해 Equals 메서드를 재정의합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 객체 | java.lang.Object | 비교할 VCard 객체. |
|

**Returns:**
boolean - 전달된 VCard 객체가 동일한 유형이며 모든 속성이 이 인스턴스의 속성과 동일하면 true를 반환합니다.

### hashCode() {#hashCode--}
```
public int hashCode()
```


GetHashCode 메서드를 재정의합니다.


**Returns:**
int - VCard 해시 코드

