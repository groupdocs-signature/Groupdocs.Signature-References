---
title: TextSearchOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 텍스트 서명에 대한 검색 옵션을 나타냅니다.
type: docs
weight: 1720
url: /ko/net/groupdocs.signature.options/textsearchoptions/
---
## TextSearchOptions class

텍스트 서명에 대한 검색 옵션을 나타냅니다.

```csharp
public class TextSearchOptions : SearchOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextSearchOptions](textsearchoptions#constructor)() | 기본값을 사용하여 TextSearchOptions 클래스의 새 인스턴스를 초기화합니다. |
| [TextSearchOptions](textsearchoptions#constructor_1)(string) | 텍스트 값을 사용하여 TextSearchOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [AllPages](../../groupdocs.signature.options/searchoptions/allpages) { get; set; } | 각 문서 페이지에서 검색할 플래그입니다. 기본적으로 이 값은 true로 설정됩니다. |
| [MatchType](../../groupdocs.signature.options/textsearchoptions/matchtype) { get; set; } | 텍스트 일치 유형 검색을 가져오거나 설정합니다. |
| [PageNumber](../../groupdocs.signature.options/searchoptions/pagenumber) { get; set; } | 검색할 문서 페이지 번호를 가져오거나 설정합니다. 값은 선택 사항입니다. |
| [PagesSetup](../../groupdocs.signature.options/searchoptions/pagessetup) { get; set; } | 서명 검색을 위한 페이지 지정 옵션. |
| [SignatureImplementation](../../groupdocs.signature.options/textsearchoptions/signatureimplementation) { get; set; } | 검색할 텍스트 서명 구현을 지정합니다. |
| [SkipExternal](../../groupdocs.signature.options/searchoptions/skipexternal) { get; set; } | IsSignature로 표시된 서명만 반환하는 플래그입니다. 기본 값은 지정된 기준과 일치하는 모든 서명을 반환함을 나타내는 false입니다. |
| [Text](../../groupdocs.signature.options/textsearchoptions/text) { get; set; } | 검색 시 일치시킬 서명 텍스트를 지정합니다. |

### 비고

**더 알아보기**

* GroupDocs.Signature에 의한 텍스트 전자 서명 검색의 기본 사용법: [ 문서에서 텍스트 서명을 eSearch하는 방법](https://docs.groupdocs.com/display/signaturenet/Search+for+Text+e-signatures)
* GroupDocs.Signature를 사용한 텍스트 전자 서명 검색 설정의 고급 사용: [문서 및 추가 설정에서 전자 검색 텍스트 서명의 고급 사용](https://docs.groupdocs.com/display/signaturenet/Advanced+search+for+Text+signatures)

### 또한보십시오

* class [SearchOptions](../searchoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->