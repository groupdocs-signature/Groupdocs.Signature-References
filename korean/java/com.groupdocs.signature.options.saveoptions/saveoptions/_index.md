---
title: "SaveOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서를 서명하기 위해 저장할 때 비밀번호와 같은 추가 옵션을 지정할 수 있습니다."
type: docs
weight: 13
url: /ko/java/com.groupdocs.signature.options.saveoptions/saveoptions/
---
**Inheritance:**
java.lang.Object
```
public class SaveOptions
```

문서를 서명하기 위해 저장할 때 추가 옵션(예: 비밀번호)을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [SaveOptions()](#SaveOptions--) | SaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |
|
|  | [SaveOptions(boolean overwriteExistingFile)](#SaveOptions-boolean-) | SaveOptions 클래스의 새 인스턴스를 지정된 출력 유형 및 덮어쓰기 플래그와 함께 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getOverwriteExistingFiles()](#getOverwriteExistingFiles--) | 기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다. |
|
|  | [setOverwriteExistingFiles(boolean value)](#setOverwriteExistingFiles-boolean-) | 기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다. |
|
|  | [getPassword()](#getPassword--) | 비밀번호 보호와 함께 서명된 문서를 저장하기 위한 비밀번호를 가져오거나 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 비밀번호 보호와 함께 서명된 문서를 저장하기 위한 비밀번호를 가져오거나 설정합니다. |
|
|  | [getUseOriginalPassword()](#getUseOriginalPassword--) | LoadOptions에서 가져온 비밀번호를 사용하여 서명된 문서를 보호된 상태로 저장할지 여부를 가져오거나 설정합니다. |
|
|  | [setUseOriginalPassword(boolean value)](#setUseOriginalPassword-boolean-) | LoadOptions에서 가져온 비밀번호를 사용하여 서명된 문서를 보호된 상태로 저장할지 여부를 가져오거나 설정합니다. |
|
|  | [getAddMissingExtenstion()](#getAddMissingExtenstion--) | 출력 파일 경로에 확장자가 없을 경우 자동으로 추가하는 플래그를 가져오거나 설정합니다. |
기본값은 false입니다.
|
|  | [setAddMissingExtenstion(boolean value)](#setAddMissingExtenstion-boolean-) | 출력 파일 경로에 확장자가 없을 경우 자동으로 추가하는 플래그를 가져오거나 설정합니다. |
기본값은 false입니다.
|
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


SaveOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.


### SaveOptions(boolean overwriteExistingFile) {#SaveOptions-boolean-}
```
public SaveOptions(boolean overwriteExistingFile)
```


SaveOptions 클래스의 새 인스턴스를 지정된 출력 유형 및 덮어쓰기 플래그와 함께 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | overwriteExistingFile | boolean | 같은 파일로 서명된 파일을 덮어쓸지 여부를 나타내는 플래그입니다. |
|

### getOverwriteExistingFiles() {#getOverwriteExistingFiles--}
```
public final boolean getOverwriteExistingFiles()
```


기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다.
그렇지 않으면 번호가 접미사로 붙은 새 파일이 생성됩니다.


**Returns:**
boolean
### setOverwriteExistingFiles(boolean value) {#setOverwriteExistingFiles-boolean-}
```
public final void setOverwriteExistingFiles(boolean value)
```


기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다.
그렇지 않으면 번호가 접미사로 붙은 새 파일이 생성됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```


비밀번호 보호와 함께 서명된 문서를 저장하기 위한 비밀번호를 가져오거나 설정합니다.
이 속성은 이미지 문서에 대해 지원되지 않습니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


비밀번호 보호와 함께 서명된 문서를 저장하기 위한 비밀번호를 가져오거나 설정합니다.
이 속성은 이미지 문서에 대해 지원되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getUseOriginalPassword() {#getUseOriginalPassword--}
```
public final boolean getUseOriginalPassword()
```


LoadOptions에서 가져온 비밀번호를 사용하여 서명된 문서를 보호된 상태로 저장할지 여부를 가져오거나 설정합니다.
기본값은 true입니다.
이 속성은 이미지 문서에 대해 지원되지 않습니다.


**Returns:**
boolean
### setUseOriginalPassword(boolean value) {#setUseOriginalPassword-boolean-}
```
public final void setUseOriginalPassword(boolean value)
```


LoadOptions에서 가져온 비밀번호를 사용하여 서명된 문서를 보호된 상태로 저장할지 여부를 가져오거나 설정합니다.
기본값은 true입니다.
이 속성은 이미지 문서에 대해 지원되지 않습니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getAddMissingExtenstion() {#getAddMissingExtenstion--}
```
public final boolean getAddMissingExtenstion()
```


출력 파일 경로에 확장자가 없을 경우 자동으로 추가하는 플래그를 가져오거나 설정합니다.
기본값은 false입니다.


**Returns:**
boolean
### setAddMissingExtenstion(boolean value) {#setAddMissingExtenstion-boolean-}
```
public final void setAddMissingExtenstion(boolean value)
```


출력 파일 경로에 확장자가 없을 경우 자동으로 추가하는 플래그를 가져오거나 설정합니다.
기본값은 false입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

