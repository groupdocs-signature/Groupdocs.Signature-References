---
title: FormFieldSearchOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 양식 필드 서명에 대한 검색 옵션을 나타냅니다.
type: docs
weight: 1370
url: /ko/net/groupdocs.signature.options/formfieldsearchoptions/
---
## FormFieldSearchOptions class

양식 필드 서명에 대한 검색 옵션을 나타냅니다.

```csharp
public class FormFieldSearchOptions : SearchOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [FormFieldSearchOptions](formfieldsearchoptions)() | FormFieldSearchOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | 각 문서 페이지에서 검색할 플래그입니다. 기본적으로 이 값은 true로 설정됩니다. |
| [Name](../../groupdocs.signature.options/formfieldsearchoptions/name) { get; set; } | 검색해야 하는 경우 양식 필드 서명 이름의 정규식 패턴을 지정합니다. "텍스트"로 간단하게 사용하거나 "abc\d+"와 같은 정규식으로 사용할 수 있습니다. 기본값은 빈 문자열입니다. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | 검색할 문서 페이지 번호를 가져오거나 설정합니다. 값은 선택 사항입니다. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | 서명 검색을 위한 페이지 지정 옵션. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | IsSignature로 표시된 서명만 반환하는 플래그입니다. 기본 값은 지정된 기준과 일치하는 모든 서명을 반환함을 나타내는 false입니다. |
| [Type](../../groupdocs.signature.options/formfieldsearchoptions/type) { get; set; } | 검색해야 하는 경우 양식 필드 서명 유형을 지정합니다. 기본값은 null입니다. |
| [Value](../../groupdocs.signature.options/formfieldsearchoptions/value) { get; set; } | 검색해야 하는 경우 양식 필드 서명 값을 지정합니다. 기본값은 null입니다. |

### 비고

**더 알아보기**

* GroupDocs.Signature에 의한 FormField 전자 서명 검색의 기본 사용법: [ 문서에서 FormField 서명을 eSearch하는 방법](https://docs.groupdocs.com/display/signaturenet/Search+for+Form+Field+e-signatures)
* GroupDocs.Signature를 사용한 FormField 전자 서명 검색 설정의 고급 사용: [문서 및 추가 설정에서 eSearch FormField 서명의 고급 사용](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Form+Field+signatures)

### 또한보십시오

* class [SearchOptions](../searchoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
