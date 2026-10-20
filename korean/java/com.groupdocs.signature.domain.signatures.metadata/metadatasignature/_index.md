---
title: "MetadataSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "메타데이터 서명 속성을 포함합니다."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.domain.signatures.metadata/metadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature)
```
public abstract class MetadataSignature extends BaseSignature
```

메타데이터 서명 속성을 포함합니다.

## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 고유 메타데이터 이름을 지정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 고유 메타데이터 이름을 지정합니다. |
|
|  | [getValue()](#getValue--) | 메타데이터 객체를 지정합니다. |
|
|  | [setValue(Object value)](#setValue-java.lang.Object-) | 메타데이터 객체를 지정합니다. |
|
|  | [getType()](#getType--) | 메타데이터 값 유형을 지정합니다. |
|
|  | [setType(int value)](#setType-int-) | 메타데이터 값 유형을 지정합니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | 서명 Value 속성을 인코딩하고 디코딩하기 위해 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 서명 Value 속성을 인코딩하고 디코딩하기 위해 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다. |
|
|  | [<T>getData(Class<T> typeOfT)](#-T-getData-java.lang.Class-T--) | 역직렬화 시 메타데이터 서명 Value에서 객체를 얻습니다. |
|
|  | [<T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)](#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | 역직렬화 시 메타데이터 서명 Text에서 객체를 얻습니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [toBoolean()](#toBoolean--) | 불리언으로 변환합니다. |
|
|  | [toInteger()](#toInteger--) | 정수형으로 변환합니다. |
|
|  | [toDouble()](#toDouble--) | Double 형식으로 변환합니다. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double 형식으로 변환합니다. |
|
|  | [toSingle()](#toSingle--) | float 형식으로 변환합니다. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | float 형식으로 변환합니다. |
|
|  | [toDateTime()](#toDateTime--) | DateTime 형식으로 변환합니다. |
|
|  | [toDateTime(Locale provider)](#toDateTime-java.util.Locale-) | DateTime 형식으로 변환합니다. |
|
|  | [toString()](#toString--) | ToString() 메서드를 재정의하여 문자열로 변환합니다. |
|
|  | [toString(String format)](#toString-java.lang.String-) | 지정된 형식으로 문자열로 변환합니다. |
|
|  | [toString(String format, Locale provider)](#toString-java.lang.String-java.util.Locale-) | 지정된 형식으로 문자열로 변환합니다. |
|
|  | [deepClone()](#deepClone--) | Metadata 서명 인스턴스를 복제합니다. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 주어진 값으로 메타데이터 서명 인스턴스를 복제합니다. |
|
### getName() {#getName--}
```
public final String getName()
```


고유 메타데이터 이름을 지정합니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


고유 메타데이터 이름을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


메타데이터 객체를 지정합니다.


**Returns:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


메타데이터 객체를 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

### getType() {#getType--}
```
public final int getType()
```


메타데이터 값 유형을 지정합니다.


**Returns:**
int
### setType(int value) {#setType-int-}
```
public final void setType(int value)
```


메타데이터 값 유형을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


서명 Value 속성을 인코딩하고 디코딩하기 위해 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


서명 Value 속성을 인코딩하고 디코딩하기 위해 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

### <T>getData(Class<T> typeOfT) {#-T-getData-java.lang.Class-T--}
```
public final T <T>getData(Class<T> typeOfT)
```


역직렬화 시 메타데이터 서명 Value에서 객체를 얻습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |

**Returns:**
T - T 객체의 인스턴스


T
: 메타데이터 값에서 역직렬화할 객체 유형

### <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption) {#-T-getData-java.lang.Class-T--com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final T <T>getData(Class<T> typeOfT, IDataEncryption dataEncryption)
```


역직렬화 시 메타데이터 서명 Text에서 객체를 얻습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| typeOfT | java.lang.Class<T> |  |
|  | dataEncryption | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) | 사용자 지정 데이터 암호화 구현을 설정합니다 |


T
: 메타데이터 Value에서 역직렬화할 객체 유형
|

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

### toBoolean() {#toBoolean--}
```
public boolean toBoolean()
```


불리언으로 변환합니다.


**Returns:**
boolean - 메타데이터 서명 값을 불리언으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />


### toInteger() {#toInteger--}
```
public int toInteger()
```


정수형으로 변환합니다.


**Returns:**
int - 메타데이터 서명 값을 정수형으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />


### toDouble() {#toDouble--}
```
public double toDouble()
```


Double 형식으로 변환합니다.


**Returns:**
double - 메타데이터 서명 값을 Double 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원본 값이 문자열 기반인 경우 SignatureSettings 속성의 기본 문화 정보인 SignatureSettings.DefaultCulture가 사용됩니다.

<br />


### toDouble(Locale provider) {#toDouble-java.util.Locale-}
```
public double toDouble(Locale provider)
```


Double 형식으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | provider | java.util.Locale | 데이터 변환 작업에 사용할 형식 데이터 제공자. |

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />

|

**Returns:**
double - 메타데이터 서명 값을 Double 형식으로 반환합니다.

### toSingle() {#toSingle--}
```
public float toSingle()
```


float 형식으로 변환합니다.


**Returns:**
float - 메타데이터 서명 값을 float 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원래 값이 문자열 기반인 경우 SignatureSettings 속성의 기본 문화 속성 정보인 SignatureSettings.DefaultCulture()가 사용됩니다.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public float toSingle(Locale provider)
```


float 형식으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | provider | java.util.Locale | 데이터 변환 작업에 사용할 형식 데이터 제공자. |

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />

|

**Returns:**
float - 메타데이터 서명 값을 float 형식으로 반환합니다.

### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


DateTime 형식으로 변환합니다.


**Returns:**
java.util.Date - 메타데이터 서명 값을 DateTime 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원본 값이 문자열 기반인 경우 SignatureSettings 속성의 기본 문화 정보인 SignatureSettings.DefaultCulture가 사용됩니다.

<br />


### toDateTime(Locale provider) {#toDateTime-java.util.Locale-}
```
public Date toDateTime(Locale provider)
```


DateTime 형식으로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | provider | java.util.Locale | 데이터 변환 작업에 사용할 형식 데이터 제공자. |

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />

|

**Returns:**
java.util.Date - 메타데이터 서명 값을 DateTime 형식으로 반환합니다.

### toString() {#toString--}
```
public String toString()
```


ToString() 메서드를 재정의하여 문자열로 변환합니다.


**Returns:**
java.lang.String - 메타데이터 서명 값을 String 형식으로 반환합니다.

<br />

*** ** * ** ***

부울 속성을 "True" 또는 "False" 로 변환합니다. 다른 데이터 유형의 경우 기본 데이터 형식 제공자가 사용됩니다.

<br />


### toString(String format) {#toString-java.lang.String-}
```
public String toString(String format)
```


지정된 형식으로 문자열로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 형식 | java.lang.String | 데이터 형식 문자열. |

<br />

*** ** * ** ***

부울 속성을 "True" 또는 "False" 로 변환합니다. SignatureSettings 속성의 기본 문화 속성 정보인 SignatureSettings.DefaultCulture가 사용됩니다.

<br />

|

**Returns:**
java.lang.String - 메타데이터 서명 값을 String 형식으로 반환합니다.

### toString(String format, Locale provider) {#toString-java.lang.String-java.util.Locale-}
```
public String toString(String format, Locale provider)
```


지정된 형식으로 문자열로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 형식 | java.lang.String | 데이터 형식 문자열. |
|
|  | provider | java.util.Locale | 데이터 변환 작업에 사용할 형식 데이터 제공자. |

<br />

*** ** * ** ***

부울 속성을 "True" 또는 "False" 로 변환합니다.

<br />

|

**Returns:**
java.lang.String - 메타데이터 서명 값을 String 형식으로 반환합니다.

### deepClone() {#deepClone--}
```
public Object deepClone()
```


Metadata 서명 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 Metadata 서명 인스턴스를 반환합니다

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


주어진 값으로 메타데이터 서명 인스턴스를 복제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 새 복제 객체의 값입니다. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance with given value.

