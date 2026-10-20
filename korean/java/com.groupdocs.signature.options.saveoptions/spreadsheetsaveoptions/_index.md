---
title: "SpreadsheetSaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "스프레드시트 문서에 대한 저장 옵션."
type: docs
weight: 14
url: /ko/java/com.groupdocs.signature.options.saveoptions/spreadsheetsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.groupdocs.signature.options.saveoptions.SaveOptions](../../com.groupdocs.signature.options.saveoptions/saveoptions)
```
public class SpreadsheetSaveOptions extends SaveOptions
```

스프레드시트 문서에 대한 저장 옵션.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SpreadsheetSaveOptions()](#SpreadsheetSaveOptions--) | 기본값으로 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [SpreadsheetSaveOptions(int fileFormat)](#SpreadsheetSaveOptions-int-) | 미리 정의된 출력 파일 형식으로 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)](#SpreadsheetSaveOptions-int-boolean-) | 지정된 출력 유형 및 덮어쓰기 플래그와 함께 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
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
### SpreadsheetSaveOptions() {#SpreadsheetSaveOptions--}
```
public SpreadsheetSaveOptions()
```


기본값으로 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다.


### SpreadsheetSaveOptions(int fileFormat) {#SpreadsheetSaveOptions-int-}
```
public SpreadsheetSaveOptions(int fileFormat)
```


미리 정의된 출력 파일 형식으로 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 형식을 지정합니다. |
|

### SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile) {#SpreadsheetSaveOptions-int-boolean-}
```
public SpreadsheetSaveOptions(int fileFormat, boolean overwriteExistingFile)
```


지정된 출력 유형 및 덮어쓰기 플래그와 함께 SpreadsheetSaveOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileFormat | int | 출력 파일 형식을 지정합니다. |
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
