---
title: "LoadOptions"
second_title: "Java용 GroupDocs.Signature API 참조"
description: "문서를 서명하기 위해 열 때 비밀번호와 같은 추가 옵션을 지정할 수 있습니다."
type: docs
weight: 10
url: /ko/java/com.groupdocs.signature.options.loadoptions/loadoptions/
---
**Inheritance:**
java.lang.Object
```
public class LoadOptions
```

문서를 서명하기 위해 열 때 비밀번호와 같은 추가 옵션을 지정할 수 있습니다.

## 생성자

| 생성자 | 설명 |
| --- | --- |
|  | [LoadOptions()](#LoadOptions--) | LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
|  | [LoadOptions(FileType fileType)](#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-) | 지정된 파일 유형으로 LoadOptions 클래스의 새 인스턴스를 초기화합니다. |
|
## 메서드

| 메서드 | 설명 |
| --- | --- |
|  | [getPassword()](#getPassword--) | 보호된 문서를 열기 위한 비밀번호를 가져오거나 설정합니다. |
|
|  | [setPassword(String value)](#setPassword-java.lang.String-) | 보호된 문서를 열기 위한 비밀번호를 가져오거나 설정합니다. |
|
|  | [getSkipExternalResources()](#getSkipExternalResources--) | 문서를 로드할 때 문서 외부에 저장된 리소스를 건너뛰는지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
|
|  | [setSkipExternalResources(boolean value)](#setSkipExternalResources-boolean-) | 문서를 로드할 때 문서 외부에 저장된 리소스를 건너뛰는지 여부를 나타내는 플래그를 가져오거나 설정합니다. |
|
|  | [getWhitelistedResources()](#getWhitelistedResources--) | 로드될 수 있는 외부 리소스 주소의 일부를 가져오거나 설정합니다. |
#getSkipExternalResources().getSkipExternalResources()가 true입니다.
|
|  | [setWhitelistedResources(List<String> value)](#setWhitelistedResources-java.util.List-java.lang.String--) | 로드될 수 있는 외부 리소스 주소의 일부를 가져오거나 설정합니다. |
#getSkipExternalResources().getSkipExternalResources()가 true입니다.
|
|  | [getPermissions()](#getPermissions--) | 인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다. |
|
|  | [setPermissions(Integer value)](#setPermissions-java.lang.Integer-) | 파일에서 파싱된 권한을 기록하기 위해 문서 로드 프로세서에서 사용하는 내부 설정자입니다. |
|
|  | [getFileType()](#getFileType--) | 문서의 파일 유형을 가져옵니다. |
|
|  | [setFileType(FileType value)](#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-) | 문서의 파일 유형을 설정하여 문서 내용에서 자동으로 감지되지 않도록 합니다. |
|
### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```


LoadOptions 클래스의 새 인스턴스를 초기화합니다.


### LoadOptions(FileType fileType) {#LoadOptions-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public LoadOptions(FileType fileType)
```


지정된 파일 유형으로 LoadOptions 클래스의 새 인스턴스를 초기화합니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | fileType | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) | 문서의 파일 유형은 #setFileType(FileType).setFileType(FileType)를 참조하십시오. |
|

### getPassword() {#getPassword--}
```
public final String getPassword()
```


보호된 문서를 열기 위한 비밀번호를 가져오거나 설정합니다.
또한 서명된 문서를 보호된 상태로 저장하는 데 사용됩니다.


**Returns:**
java.lang.String
### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```


보호된 문서를 열기 위한 비밀번호를 가져오거나 설정합니다.
또한 서명된 문서를 보호된 상태로 저장하는 데 사용됩니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String |  |

### getSkipExternalResources() {#getSkipExternalResources--}
```
public final boolean getSkipExternalResources()
```


문서를 로드할 때 문서 외부에 저장된 리소스를 건너뛰는지 여부를 나타내는 플래그를 가져오거나 설정합니다.
기본값은 true입니다.


문서는 외부 리소스를 참조할 수 있습니다: 워드 프로세싱에서 연결된 이미지와 INCLUDEPICTURE 필드
문서, 프레젠테이션 및 스프레드시트의 연결된 그림, 이미지 및 SVG 이미지가 참조하는 스타일 시트.
이러한 리소스를 로드한다는 것은 문서에 기록된 주소를 요청하는 것을 의미합니다. 이를 처리하는 서버에서는
다른 사람의 문서를 처리할 때 서버 측 요청 위조 위험이 있으며, 오프라인 설치에서는
요청이 실패하거나 시간 초과를 기다립니다.


true인 경우, 주소에 다음 중 하나가 포함된 경우를 제외하고 외부 리소스를 로드하지 않습니다.
#getWhitelistedResources().getWhitelistedResources(). 건너뛴 리소스는 페이지 미리보기나 저장된 문서에 그려지지 않습니다.
이미지와 이미지, 바코드 및 QR-코드 검색에서는 이를 볼 수 없습니다. 포함된 이미지는 영향을 받지 않으며, 그리고
하이퍼링크는 절대 따라가지 않습니다. 이 설정은 아카이브 내부의 문서에도 적용됩니다.


**Returns:**
boolean
### setSkipExternalResources(boolean value) {#setSkipExternalResources-boolean-}
```
public final void setSkipExternalResources(boolean value)
```


문서를 로드할 때 문서 외부에 저장된 리소스를 건너뛰는지 여부를 나타내는 플래그를 가져오거나 설정합니다.
기본값은 true입니다. #getSkipExternalResources().getSkipExternalResources()를 참조하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean |  |

### getWhitelistedResources() {#getWhitelistedResources--}
```
public final List<String> getWhitelistedResources()
```


로드될 수 있는 외부 리소스 주소의 일부를 가져오거나 설정합니다.
#getSkipExternalResources().getSkipExternalResources()는 true입니다. 주소에 그 중 하나가 포함되어 있으면(대소문자 무시) 로드됩니다.
빈 값은 무시됩니다. 기본값은 빈 목록이며; null을 설정하면 이를 비웁니다.


**Returns:**
java.util.List<java.lang.String>
### setWhitelistedResources(List<String> value) {#setWhitelistedResources-java.util.List-java.lang.String--}
```
public final void setWhitelistedResources(List<String> value)
```


로드될 수 있는 외부 리소스 주소의 일부를 가져오거나 설정합니다.
#getSkipExternalResources().getSkipExternalResources()는 true입니다. #getWhitelistedResources().getWhitelistedResources()를 참조하십시오.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.util.List<java.lang.String> |  |

### getPermissions() {#getPermissions--}
```
public final Integer getPermissions()
```


인쇄, 수정 및 데이터 추출과 같은 PDF 문서 권한입니다.
PDF 문서에만 적용됩니다. 읽기 전용 \\u2014 문서를 로드하는 동안 자동으로 채워집니다.
값은 [Permissions](../../com.groupdocs.signature.options/permissions)에서 가져온 플래그 조합입니다.


**Returns:**
java.lang.Integer
### setPermissions(Integer value) {#setPermissions-java.lang.Integer-}
```
public final void setPermissions(Integer value)
```


파일에서 파싱된 권한을 기록하기 위해 문서 로드 프로세서에서 사용하는 내부 설정자입니다.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.Integer |  |

### getFileType() {#getFileType--}
```
public final FileType getFileType()
```


문서의 파일 유형을 가져옵니다. 파일 유형이 [FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (기본값)인 경우,
파일 유형은 문서 내용으로부터 감지됩니다.


**Returns:**
[FileType](../../com.groupdocs.signature.domain.documentpreview/filetype)
### setFileType(FileType value) {#setFileType-com.groupdocs.signature.domain.documentpreview.FileType-}
```
public final void setFileType(FileType value)
```


문서의 파일 유형을 설정하여 문서 내용에서 자동으로 감지되지 않도록 합니다.
[FileType.Unknown](../../com.groupdocs.signature.domain.documentpreview/filetype#Unknown) (the default) or null detects it.


**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [FileType](../../com.groupdocs.signature.domain.documentpreview/filetype) |  |

