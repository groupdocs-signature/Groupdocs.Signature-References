---
title: "MetadataSearchOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "메타데이터 서명에 대한 추상 검색 옵션을 나타냅니다."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.options.search/metadatasearchoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.OptionsExtensions](../../com.groupdocs.signature.options/optionsextensions), [com.groupdocs.signature.options.search.SearchOptions](../../com.groupdocs.signature.options.search/searchoptions)
```
public class MetadataSearchOptions extends SearchOptions
```

메타데이터 서명에 대한 추상 검색 옵션을 나타냅니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [MetadataSearchOptions()](#MetadataSearchOptions--) | SearchMetadataOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getName()](#getName--) | 검색 및 일치시킬 메타데이터 서명 이름을 지정합니다. |
|
|  | [setName(String value)](#setName-java.lang.String-) | 검색 및 일치시킬 메타데이터 서명 이름을 지정합니다. |
|
|  | [getNameMatchType()](#getNameMatchType--) | 메타데이터 이름 일치 유형 검색을 가져오거나 설정합니다. |
|
|  | [setNameMatchType(int value)](#setNameMatchType-int-) | 메타데이터 이름 일치 유형 검색을 가져오거나 설정합니다. |
|
|  | [getIncludeBuiltinProperties()](#getIncludeBuiltinProperties--) | 문서 통계, 정보 등과 같은 내장 문서 속성을 검색 결과에 포함시킬지 여부를 나타냅니다. |
|
|  | [setIncludeBuiltinProperties(boolean value)](#setIncludeBuiltinProperties-boolean-) | 문서 통계, 정보 등과 같은 내장 문서 속성을 검색 결과에 포함시킬지 여부를 나타냅니다. |
|
|  | [getDataEncryption()](#getDataEncryption--) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
|  | [setDataEncryption(IDataEncryption value)](#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-) | QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다. |
|
### MetadataSearchOptions() {#MetadataSearchOptions--}
```
public MetadataSearchOptions()
```


SearchMetadataOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### getName() {#getName--}
```
public final String getName()
```


검색 및 일치시킬 메타데이터 서명 이름을 지정합니다.


**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


검색 및 일치시킬 메타데이터 서명 이름을 지정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getNameMatchType() {#getNameMatchType--}
```
public final int getNameMatchType()
```


메타데이터 이름 일치 유형 검색을 가져오거나 설정합니다. 이는 Name 속성이 설정된 경우에만 사용됩니다.


**Returns:**
int
### setNameMatchType(int value) {#setNameMatchType-int-}
```
public final void setNameMatchType(int value)
```


메타데이터 이름 일치 유형 검색을 가져오거나 설정합니다. 이는 Name 속성이 설정된 경우에만 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getIncludeBuiltinProperties() {#getIncludeBuiltinProperties--}
```
public final boolean getIncludeBuiltinProperties()
```


문서 통계, 정보 등과 같은 내장 문서 속성을 검색 결과에 포함시킬지 여부를 나타냅니다.
이 플래그는 프레젠테이션, Spreadhsheet 및 워드 프로세싱 문서 파일 유형에 의미가 있습니다.


**Returns:**
boolean
### setIncludeBuiltinProperties(boolean value) {#setIncludeBuiltinProperties-boolean-}
```
public final void setIncludeBuiltinProperties(boolean value)
```


문서 통계, 정보 등과 같은 내장 문서 속성을 검색 결과에 포함시킬지 여부를 나타냅니다.
이 플래그는 프레젠테이션, Spreadhsheet 및 워드 프로세싱 문서 파일 유형에 의미가 있습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getDataEncryption() {#getDataEncryption--}
```
public final IDataEncryption getDataEncryption()
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Returns:**
[IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption)
### setDataEncryption(IDataEncryption value) {#setDataEncryption-com.groupdocs.signature.domain.extensions.encryption.IDataEncryption-}
```
public final void setDataEncryption(IDataEncryption value)
```


QR-Code 서명 텍스트 또는 데이터 속성을 인코딩하고 디코딩하기 위한 [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) 인터페이스 구현을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [IDataEncryption](../../com.groupdocs.signature.domain.extensions.encryption/idataencryption) |  |

