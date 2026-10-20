---
title: "PresentationSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "프레젠테이션 문서에 대한 저장 옵션."
type: docs
weight: 12
url: /ko/java/com.groupdocs.signature.options.saveoptions/presentationsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PresentationSaveOptions extends SaveOptions
```

프레젠테이션 문서에 대한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PresentationSaveOptions()](#PresentationSaveOptions--) | PresentationSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [PresentationSaveOptions(int fileFormat)](#PresentationSaveOptions-int-) | PresentationSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다. |
|
|  | [PresentationSaveOptions(boolean overwriteExistingFile)](#PresentationSaveOptions-boolean-) | PresentationSaveOptions 클래스의 새 인스턴스를 지정된 출력 유형 및 덮어쓰기 플래그와 함께 초기화합니다. |
|
|  | [PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PresentationSaveOptions-int-boolean-) | 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### PresentationSaveOptions() {#PresentationSaveOptions--}
```
public PresentationSaveOptions()
```


PresentationSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### PresentationSaveOptions(int fileFormat) {#PresentationSaveOptions-int-}
```
public PresentationSaveOptions(int fileFormat)
```


PresentationSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
|

### PresentationSaveOptions(boolean overwriteExistingFile) {#PresentationSaveOptions-boolean-}
```
public PresentationSaveOptions(boolean overwriteExistingFile)
```


PresentationSaveOptions 클래스의 새 인스턴스를 지정된 출력 유형 및 덮어쓰기 플래그와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
|

### PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PresentationSaveOptions-int-boolean-}
```
public PresentationSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [PresentationSaveFileFormat](../../com.groupdocs.signature.domain.enums/presentationsavefileformat). |
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

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
