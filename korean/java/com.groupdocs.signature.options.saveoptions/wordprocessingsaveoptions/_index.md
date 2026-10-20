---
title: "WordProcessingSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "워드 프로세싱 문서에 대한 저장 옵션."
type: docs
weight: 15
url: /ko/java/com.groupdocs.signature.options.saveoptions/wordprocessingsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class WordProcessingSaveOptions extends SaveOptions
```

워드 프로세싱 문서에 대한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [WordProcessingSaveOptions()](#WordProcessingSaveOptions--) | 기본값으로 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [WordProcessingSaveOptions(int fileFormat)](#WordProcessingSaveOptions-int-) | 지정된 출력 파일 형식으로 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [WordProcessingSaveOptions(boolean overwriteExistingFile)](#WordProcessingSaveOptions-boolean-) | 지정된 출력 유형 및 덮어쓰기 플래그와 함께 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)](#WordProcessingSaveOptions-int-boolean-) | 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [getOoxmlCompliance()](#getOoxmlCompliance--) | 서명된 문서에 대한 선택적 OOXML 호환성 수준입니다. |
|
|  | [setOoxmlCompliance(Integer value)](#setOoxmlCompliance-java.lang.Integer-) | 서명된 문서에 대한 선택적 OOXML 호환성 수준입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다 |
|
### WordProcessingSaveOptions() {#WordProcessingSaveOptions--}
```
public WordProcessingSaveOptions()
```


기본값으로 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다.


### WordProcessingSaveOptions(int fileFormat) {#WordProcessingSaveOptions-int-}
```
public WordProcessingSaveOptions(int fileFormat)
```


지정된 출력 파일 형식으로 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|

### WordProcessingSaveOptions(boolean overwriteExistingFile) {#WordProcessingSaveOptions-boolean-}
```
public WordProcessingSaveOptions(boolean overwriteExistingFile)
```


지정된 출력 유형 및 덮어쓰기 플래그와 함께 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
|

### WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile) {#WordProcessingSaveOptions-int-boolean-}
```
public WordProcessingSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 WordProcessingSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [WordProcessingSaveFileFormat](../../com.groupdocs.signature.domain.enums/wordprocessingsavefileformat). |
|
|  | overwriteExistingFile | boolean | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
|

### getFileFormat() {#getFileFormat--}
```
public final int getFileFormat()
```


서명된 문서의 파일 형식을 가져오거나 설정합니다.


**Returns:**
int
### setFileFormat(int value) {#setFileFormat-int-}
```
public final void setFileFormat(int value)
```


서명된 문서의 파일 형식을 가져오거나 설정합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int |  |

### getOoxmlCompliance() {#getOoxmlCompliance--}
```
public final Integer getOoxmlCompliance()
```


서명된 문서에 대한 선택적 OOXML 호환성 수준입니다. 설정하면, 다음을 재정의합니다.
원본 문서의 호환성. 경우
null
(기본값), 로드된 문서의
호환성이 유지됩니다. OOXML 형식에만 적용됩니다
(Docx, Docm, Dotx, Dotm, FlatOpc 및 FlatOpc 변형).


값은 [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) 중 하나입니다.


**Returns:**
java.lang.Integer
### setOoxmlCompliance(Integer value) {#setOoxmlCompliance-java.lang.Integer-}
```
public final void setOoxmlCompliance(Integer value)
```


서명된 문서에 대한 선택적 OOXML 호환성 수준입니다. 설정하면, 다음을 재정의합니다.
원본 문서의 호환성. 경우
null
(기본값), 로드된 문서의
호환성이 유지됩니다. OOXML 형식에만 적용됩니다
(Docx, Docm, Dotx, Dotm, FlatOpc 및 FlatOpc 변형).


값은 [OoxmlCompliance](../../com.groupdocs.signature.domain.enums/ooxmlcompliance) 중 하나입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다


**Returns:**
java.lang.String -
