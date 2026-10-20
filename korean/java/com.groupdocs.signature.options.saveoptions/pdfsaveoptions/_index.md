---
title: "PdfSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "PDF 문서에 대한 저장 옵션."
type: docs
weight: 11
url: /ko/java/com.groupdocs.signature.options.saveoptions/pdfsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class PdfSaveOptions extends SaveOptions
```

PDF 문서에 대한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [PdfSaveOptions()](#PdfSaveOptions--) | PdfSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [PdfSaveOptions(int fileFormat)](#PdfSaveOptions-int-) | PdfSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다. |
|
|  | [PdfSaveOptions(boolean overwriteExistingFile)](#PdfSaveOptions-boolean-) | PdfSaveOptions 클래스의 새 인스턴스를 덮어쓰기 플래그와 함께 초기화합니다. |
|
|  | [PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)](#PdfSaveOptions-int-boolean-) | PdfSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getFileFormat()](#getFileFormat--) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [setFileFormat(int value)](#setFileFormat-int-) | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
|
|  | [getPermissionsPassword()](#getPermissionsPassword--) | 권한 비밀번호(주 비밀번호)는 권한 설정을 변경하려면 비밀번호가 필요합니다. |
|
|  | [setPermissionsPassword(String value)](#setPermissionsPassword-java.lang.String-) | 권한 비밀번호(주 비밀번호)는 권한 설정을 변경하려면 비밀번호가 필요합니다. |
|
|  | [getPermissions()](#getPermissions--) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다. |
|
|  | [toString()](#toString--) | 문자열 변환을 재정의합니다. |
|
### PdfSaveOptions() {#PdfSaveOptions--}
```
public PdfSaveOptions()
```


PdfSaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### PdfSaveOptions(int fileFormat) {#PdfSaveOptions-int-}
```
public PdfSaveOptions(int fileFormat)
```


PdfSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식으로 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
|

### PdfSaveOptions(boolean overwriteExistingFile) {#PdfSaveOptions-boolean-}
```
public PdfSaveOptions(boolean overwriteExistingFile)
```


PdfSaveOptions 클래스의 새 인스턴스를 덮어쓰기 플래그와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
|

### PdfSaveOptions(int fileFormat, boolean overwriteExistingFile) {#PdfSaveOptions-int-boolean-}
```
public PdfSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


PdfSaveOptions 클래스의 새 인스턴스를 지정된 출력 파일 형식 및 덮어쓰기 플래그와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 유형 [PdfSaveFileFormat](../../com.groupdocs.signature.domain.enums/pdfsavefileformat). |
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

### getPermissionsPassword() {#getPermissionsPassword--}
```
public final String getPermissionsPassword()
```


권한 비밀번호(주 비밀번호)는 권한 설정을 변경하려면 비밀번호가 필요합니다.


**Returns:**
java.lang.String
### setPermissionsPassword(String value) {#setPermissionsPassword-java.lang.String-}
```
public final void setPermissionsPassword(String value)
```


권한 비밀번호(주 비밀번호)는 권한 설정을 변경하려면 비밀번호가 필요합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다.


이러한 권한을 수정하려면,
PermissionsPassword
설정되어야 합니다.
값은 [Permissions](../../com.groupdocs.signature.options/permissions)에서 가져온 플래그 조합입니다.
A
null
값은 명시적인 권한이 적용되지 않음을 의미합니다.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### toString() {#toString--}
```
public String toString()
```


문자열 변환을 재정의합니다.


**Returns:**
java.lang.String -
