---
title: "SpreadsheetMetadataSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스프레드시트 메타데이터 서명 속성을 포함합니다."
type: docs
weight: 17
url: /ko/java/com.groupdocs.signature.domain.signatures.metadata/spreadsheetmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class SpreadsheetMetadataSignature extends MetadataSignature
```

스프레드시트 메타데이터 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetMetadataSignature(String name)](#SpreadsheetMetadataSignature-java.lang.String-) | 미리 정의된 이름과 빈 값을 가진 Spreadsheet Metadata Signature 를 생성합니다. |
|
|  | [SpreadsheetMetadataSignature(String name, Object value)](#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-) | 미리 정의된 값을 가진 Spreadsheet Metadata Signature 를 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [deepClone()](#deepClone--) | Metadata 서명 인스턴스를 복제합니다. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 주어진 값을 사용하여 Spreadsheet Metadata Signature 인스턴스를 복제합니다. |
|
|  | [toString()](#toString--) | ToString() 메서드를 재정의하여 문자열로 변환합니다. |
|
|  | [toString(String format, System.IFormatProvider provider)](#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-) | 지정된 형식으로 문자열로 변환합니다. |
|
### SpreadsheetMetadataSignature(String name) {#SpreadsheetMetadataSignature-java.lang.String-}
```
public SpreadsheetMetadataSignature(String name)
```


미리 정의된 이름과 빈 값을 가진 Spreadsheet Metadata Signature 를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Spreadsheet Metadata Signature 이름. |
|

### SpreadsheetMetadataSignature(String name, Object value) {#SpreadsheetMetadataSignature-java.lang.String-java.lang.Object-}
```
public SpreadsheetMetadataSignature(String name, Object value)
```


미리 정의된 값을 가진 Spreadsheet Metadata Signature 를 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | 메타데이터 서명 객체의 이름. |
|
|  | 값 | java.lang.Object | 메타데이터 서명의 값. |
|

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


주어진 값을 사용하여 Spreadsheet Metadata Signature 인스턴스를 복제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 새 복제 객체의 값입니다. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

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


### toString(String format, System.IFormatProvider provider) {#toString-java.lang.String-com.aspose.ms.System.IFormatProvider-}
```
public String toString(String format, System.IFormatProvider provider)
```


지정된 형식으로 문자열로 변환합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 형식 | java.lang.String | 데이터 형식 문자열. |
|
|  | provider | com.aspose.ms.System.IFormatProvider | 데이터 변환 작업에 사용할 형식 데이터 제공자. |

<br />

*** ** * ** ***

부울 속성을 "True" 또는 "False" 로 변환합니다.

<br />

|

**Returns:**
java.lang.String - 메타데이터 서명 값을 String 형식으로 반환합니다.

