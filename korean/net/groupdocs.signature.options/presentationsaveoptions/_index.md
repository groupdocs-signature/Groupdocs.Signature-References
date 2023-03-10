---
title: PresentationSaveOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 프리젠테이션 문서 옵션 저장.
type: docs
weight: 1570
url: /ko/net/groupdocs.signature.options/presentationsaveoptions/
---
## PresentationSaveOptions class

프리젠테이션 문서 옵션 저장.

```csharp
public class PresentationSaveOptions : SaveOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [PresentationSaveOptions](presentationsaveoptions#constructor)() | 기본값으로 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_1)(bool) | 지정된 출력 유형 및 덮어쓰기 플래그를 사용하여 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_2)(PresentationSaveFileFormat) | 지정된 출력 파일 형식으로 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다. |
| [PresentationSaveOptions](presentationsaveoptions#constructor_3)(PresentationSaveFileFormat, bool) | 지정된 출력 파일 형식 및 덮어쓰기 플래그를 사용하여 PresentationSaveOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AddMissingExtenstion](../../groupdocs.signature.options/saveoptions/addmissingextenstion) { get; set; } | 출력 파일 path 에서 확장자가 누락된 경우 자동으로 확장자를 추가하도록 플래그를 가져오거나 설정합니다. 기본값은 false입니다. |
| [FileFormat](../../groupdocs.signature.options/presentationsaveoptions/fileformat) { get; set; } | 서명된 문서의 파일 형식을 가져오거나 설정합니다. |
| [OverwriteExistingFiles](../../groupdocs.signature.options/saveoptions/overwriteexistingfiles) { get; set; } | 기존 파일을 새 출력 파일로 덮어쓸지 여부를 가져오거나 설정합니다. 그렇지 않으면 번호가 접미사인 새 파일이 생성됩니다. 기본적으로 이 값은 true로 설정되어 파일을 덮어씁니다. |
| [Password](../../groupdocs.signature.options/saveoptions/password) { get; set; } | 암호로 보호된 서명된 문서를 저장하기 위한 암호를 가져오거나 설정합니다. 이 속성은 이미지 문서에 지원되지 않습니다. |
| [UseOriginalPassword](../../groupdocs.signature.options/saveoptions/useoriginalpassword) { get; set; } | 서명된 문서를 보호된 문서로 저장하기 위해 LoadOptions에서 암호를 사용할지 여부를 가져오거나 설정합니다. 기본값은 true입니다. 이 속성은 이미지 문서에 지원되지 않습니다. |

### 또한보십시오

* class [SaveOptions](../saveoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->