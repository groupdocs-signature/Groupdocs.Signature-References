---
title: "PdfMetadataSignature"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 메타데이터 서명 속성을 포함합니다."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.domain.signatures.metadata/pdfmetadatasignature/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.domain.signatures.BaseSignature](../../com.groupdocs.signature.domain.signatures/basesignature), [com.groupdocs.signature.domain.signatures.metadata.MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature)
```
public final class PdfMetadataSignature extends MetadataSignature
```

PDF 메타데이터 서명 속성을 포함합니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfMetadataSignature(String name)](#PdfMetadataSignature-java.lang.String-) | 미리 정의된 이름과 빈 값을 가진 Pdf 메타데이터 서명을 생성합니다. |
|
|  | [PdfMetadataSignature(String name, Object value)](#PdfMetadataSignature-java.lang.String-java.lang.Object-) | 미리 정의된 값을 가진 Pdf 메타데이터 서명을 생성합니다. |
|
|  | [PdfMetadataSignature(String name, Object value, String tag)](#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-) | 미리 정의된 값을 가진 Pdf 메타데이터 서명을 생성합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getTagPrefix()](#getTagPrefix--) | Pdf 메타데이터 서명 이름의 접두사 태그입니다. |
|
|  | [setTagPrefix(String value)](#setTagPrefix-java.lang.String-) | Pdf 메타데이터 서명 이름의 접두사 태그입니다. |
|
|  | [equals(Object signature)](#equals-java.lang.Object-) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다. |
|
|  | [hashCode()](#hashCode--) | GetHashCode 메서드를 재정의합니다. |
|
|  | [deepClone()](#deepClone--) | Metadata 서명 인스턴스를 복제합니다. |
|
|  | [deepClone(Object value)](#deepClone-java.lang.Object-) | 주어진 값을 사용하여 Pdf 메타데이터 서명 인스턴스를 복제합니다. |
|
### PdfMetadataSignature(String name) {#PdfMetadataSignature-java.lang.String-}
```
public PdfMetadataSignature(String name)
```


미리 정의된 이름과 빈 값을 가진 Pdf 메타데이터 서명을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Pdf 메타데이터 서명 이름 |
|

### PdfMetadataSignature(String name, Object value) {#PdfMetadataSignature-java.lang.String-java.lang.Object-}
```
public PdfMetadataSignature(String name, Object value)
```


미리 정의된 값을 가진 Pdf 메타데이터 서명을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Metadata 서명 객체의 이름 |
|
|  | 값 | java.lang.Object | Metadata 서명의 값 |
|

### PdfMetadataSignature(String name, Object value, String tag) {#PdfMetadataSignature-java.lang.String-java.lang.Object-java.lang.String-}
```
public PdfMetadataSignature(String name, Object value, String tag)
```


미리 정의된 값을 가진 Pdf 메타데이터 서명을 생성합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 이름 | java.lang.String | Metadata 서명 객체의 이름 |
|
|  | 값 | java.lang.Object | Metadata 서명의 값 |
|
|  | 태그 | java.lang.String | Metadata 서명의 접두사 태그 |
|

### getTagPrefix() {#getTagPrefix--}
```
public final String getTagPrefix()
```


Pdf 메타데이터 서명 이름의 접두사 태그입니다. 기본적으로 이 속성은 "xmp"로 설정됩니다.
가능한 값은 다음과 같습니다.


**Returns:**
java.lang.String
### setTagPrefix(String value) {#setTagPrefix-java.lang.String-}
```
public final void setTagPrefix(String value)
```


Pdf 메타데이터 서명 이름의 접두사 태그입니다. 기본적으로 이 속성은 "xmp"로 설정됩니다.
가능한 값은 다음과 같습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

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


주어진 값을 사용하여 Pdf 메타데이터 서명 인스턴스를 복제합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 값 | java.lang.Object | 새 복제 객체의 값입니다. |
|

**Returns:**
[MetadataSignature](../../com.groupdocs.signature.domain.signatures.metadata/metadatasignature) - Returns cloned Metadata Signature instance.

