---
title: "ImageMetadataSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "이미지 메타데이터 서명 속성을 포함합니다."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class ImageMetadataSignature extends MetadataSignature
```

이미지 메타데이터 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [ImageMetadataSignature(int id, Object value)](#ImageMetadataSignature-int-java.lang.Object-) | Id와 값을 사용하여 Image Metadata Signature를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getId()](#getId--) | Image Metadata 서명의 식별자입니다. |
|
|  | [setId(int value)](#setId-int-) | Image Metadata 서명의 식별자입니다. |
|
|  | [getSize()](#getSize--) | 메타데이터 값의 크기를 가져오기 위한 읽기 전용 값 |
|
|  | [setSize(int value)](#setSize-int-) | 메타데이터 값의 크기를 가져오기 위한 읽기 전용 값 |
|
|  | [getDescription()](#getDescription--) | 표준 Image Metadata 서명의 설명을 가져오기 위한 읽기 전용 값 |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Metadata 서명 인스턴스를 복제합니다. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 주어진 값을 사용하여 Image Metadata Signature 인스턴스를 복제합니다. |
|
|  | [toBoolean()](#toBoolean--) | 불리언으로 변환합니다. |
|
|  | [toInteger()](#toInteger--) | 정수형으로 변환합니다. |
|
|  | [toLong()](#toLong--) | long 형식으로 변환합니다. |
|
|  | [toSingle()](#toSingle--) | float 형식으로 변환합니다. |
|
|  | [toSingle(Locale provider)](#toSingle-java.util.Locale-) | float 형식으로 변환합니다. |
|
|  | [toDouble()](#toDouble--) | Double 형식으로 변환합니다. |
|
|  | [toDouble(Locale provider)](#toDouble-java.util.Locale-) | Double 형식으로 변환합니다. |
|
|  | [toDecimal()](#toDecimal--) | Decimal 로 변환합니다. |
|
|  | [toDecimal(Locale provider)](#toDecimal-java.util.Locale-) | Decimal 로 변환합니다. |
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
| [setAsBool(Object value)](#setAsBool-java.lang.Object-) |  |
| [setAsByte(Object value)](#setAsByte-java.lang.Object-) |  |
| [setAsShrt(Object value)](#setAsShrt-java.lang.Object-) |  |
| [setAsWord(Object value)](#setAsWord-java.lang.Object-) |  |
| [setAsSInt(Object value)](#setAsSInt-java.lang.Object-) |  |
| [setAsUInt(Object value)](#setAsUInt-java.lang.Object-) |  |
| [setAsSLng(Object value)](#setAsSLng-java.lang.Object-) |  |
| [setAsULng(Object value)](#setAsULng-java.lang.Object-) |  |
| [setAsSngl(Object value)](#setAsSngl-java.lang.Object-) |  |
| [setAsDbls(Object value)](#setAsDbls-java.lang.Object-) |  |
| [setAsDcml(Object value)](#setAsDcml-java.lang.Object-) |  |
| [setAsDate(Object value)](#setAsDate-java.lang.Object-) |  |
| [setAsStrn(Object value)](#setAsStrn-java.lang.Object-) |  |
| [setAsObjc(Object value)](#setAsObjc-java.lang.Object-) |  |
| [setString(Object value)](#setString-java.lang.Object-) |  |
### ImageMetadataSignature(int id, Object value) {#ImageMetadataSignature-int-java.lang.Object-}
```
public ImageMetadataSignature(int id, Object value)
```


Id와 값을 사용하여 Image Metadata Signature를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | id | int | 이미지 메타데이터 서명 이름의 고유 식별자입니다. 가능한 id 값에 대한 Exif 태그 사양은 참고 문서를 확인하십시오. |
|
|  | 값 | java.lang.Object | 메타데이터 값 |
|

### getId() {#getId--}
```
public final int getId()
```


Image Metadata 서명의 식별자입니다.
표준 서명을 포함하고 미리 정의된 Id 값을 가진 [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) 클래스를 확인하십시오.


**Returns:**
int
### setId(int value) {#setId-int-}
```
public final void setId(int value)
```


Image Metadata 서명의 식별자입니다.
표준 서명을 포함하고 미리 정의된 Id 값을 가진 [ImageMetadataSignatures](../../com.groupdocs.signature.domain.signatures.metadata/imagemetadatasignatures) 클래스를 확인하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getSize() {#getSize--}
```
public final int getSize()
```


메타데이터 값의 크기를 가져오기 위한 읽기 전용 값


**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public final void setSize(int value)
```


메타데이터 값의 크기를 가져오기 위한 읽기 전용 값


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```


표준 Image Metadata 서명의 설명을 가져오기 위한 읽기 전용 값


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


Metadata 서명 인스턴스를 복제합니다.


**Returns:**
java.lang.Object - 복제된 Metadata 서명 인스턴스를 반환합니다

### deepClone(Object value) {#deepClone-java.lang.Object-}
```
public MetadataSignature deepClone(Object value)
```


주어진 값을 사용하여 Image Metadata Signature 인스턴스를 복제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 새 복제 객체의 값입니다. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

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


### toLong() {#toLong--}
```
public final long toLong()
```


long 형식으로 변환합니다.


**Returns:**
long - 메타데이터 서명 값을 long 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다.

<br />


### toSingle() {#toSingle--}
```
public final float toSingle()
```


float 형식으로 변환합니다.


**Returns:**
float - 이미지 메타데이터 서명 값을 float 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원본 값이 문자열 기반인 경우 SignatureSettings 속성의 기본 문화 정보인 SignatureSettings.DefaultCulture가 사용됩니다.

<br />


### toSingle(Locale provider) {#toSingle-java.util.Locale-}
```
public final float toSingle(Locale provider)
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

### toDouble() {#toDouble--}
```
public double toDouble()
```


Double 형식으로 변환합니다.


**Returns:**
double - 이미지 메타데이터 서명 값을 Double 형식으로 반환합니다.

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

### toDecimal() {#toDecimal--}
```
public final BigDecimal toDecimal()
```


Decimal 로 변환합니다.


**Returns:**
java.math.BigDecimal - 이미지 메타데이터 서명 값을 Decimal 형식으로 반환합니다.

<br />

*** ** * ** ***

메타데이터 값을 변환할 수 없을 경우 예외를 발생시킵니다. 원본 값이 문자열 기반인 경우 SignatureSettings 속성의 기본 문화 정보인 SignatureSettings.DefaultCulture가 사용됩니다.

<br />


### toDecimal(Locale provider) {#toDecimal-java.util.Locale-}
```
public final BigDecimal toDecimal(Locale provider)
```


Decimal 로 변환합니다.


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
java.math.BigDecimal - 메타데이터 서명 값을 Decimal 형식으로 반환합니다.

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

### setAsBool(Object value) {#setAsBool-java.lang.Object-}
```
public final boolean setAsBool(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsByte(Object value) {#setAsByte-java.lang.Object-}
```
public final boolean setAsByte(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsShrt(Object value) {#setAsShrt-java.lang.Object-}
```
public final boolean setAsShrt(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsWord(Object value) {#setAsWord-java.lang.Object-}
```
public final boolean setAsWord(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsSInt(Object value) {#setAsSInt-java.lang.Object-}
```
public final boolean setAsSInt(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsUInt(Object value) {#setAsUInt-java.lang.Object-}
```
public final boolean setAsUInt(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsSLng(Object value) {#setAsSLng-java.lang.Object-}
```
public final boolean setAsSLng(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsULng(Object value) {#setAsULng-java.lang.Object-}
```
public final boolean setAsULng(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsSngl(Object value) {#setAsSngl-java.lang.Object-}
```
public final boolean setAsSngl(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsDbls(Object value) {#setAsDbls-java.lang.Object-}
```
public final boolean setAsDbls(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsDcml(Object value) {#setAsDcml-java.lang.Object-}
```
public final boolean setAsDcml(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsDate(Object value) {#setAsDate-java.lang.Object-}
```
public final boolean setAsDate(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsStrn(Object value) {#setAsStrn-java.lang.Object-}
```
public final boolean setAsStrn(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setAsObjc(Object value) {#setAsObjc-java.lang.Object-}
```
public final boolean setAsObjc(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

**Returns:**
boolean
### setString(Object value) {#setString-java.lang.Object-}
```
public final void setString(Object value)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Object |  |

