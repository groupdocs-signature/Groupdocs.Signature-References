---
title: TextShadow
second_title: .NET API 참조용 GroupDocs.Signature
description: 텍스트 서명의 텍스트 그림자 속성을 나타냅니다. 결과는 서명 유형 및 문서 형식에 따라 다를 수 있습니다. TextShadow는 지원되는 모든 문서 유형에 대해 TextAsImage 서명과 함께 사용하는 것이 좋습니다. 스프레드시트용 워터마크로 간단한 TextSignature 및 TextSignature와 함께 .xslx 및 프리젠테이션.pptx. 단어용 단순 텍스트 서명.docx도 권장되지만 기능이 제한됩니다.
type: docs
weight: 400
url: /ko/net/groupdocs.signature.domain.extensions/textshadow/
---
## TextShadow class

텍스트 서명의 텍스트 그림자 속성을 나타냅니다. 결과는 서명 유형 및 문서 형식에 따라 다를 수 있습니다. TextShadow는 지원되는 모든 문서 유형에 대해 TextAsImage 서명과 함께 사용하는 것이 좋습니다. 스프레드시트용 워터마크로 간단한 TextSignature 및 TextSignature와 함께( .xslx) 및 프리젠테이션(.pptx). 단어용 단순 텍스트 서명(.docx)도 권장되지만 기능이 제한됩니다.

```csharp
public class TextShadow : SignatureExtension
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [TextShadow](textshadow)() | 기본 옵션으로 TextShadow를 만듭니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Angle](../../groupdocs.signature.domain.extensions/textshadow/angle) { get; set; } | 텍스트를 기준으로 그림자를 배치하기 위한 각도를 가져오거나 설정합니다. 기본값은 0입니다. |
| [Blur](../../groupdocs.signature.domain.extensions/textshadow/blur) { get; set; } | 그림자의 흐림을 가져오거나 설정합니다. 기본값은 4입니다. |
| [Color](../../groupdocs.signature.domain.extensions/textshadow/color) { get; set; } | 그림자의 색상을 가져오거나 설정합니다. 기본값은 검은색입니다. |
| [Distance](../../groupdocs.signature.domain.extensions/textshadow/distance) { get; set; } | 텍스트에서 그림자까지의 거리를 가져오거나 설정합니다. 기본값은 1입니다. |
| [Transparency](../../groupdocs.signature.domain.extensions/textshadow/transparency) { get; set; } | 그림자의 투명도를 가져오거나 설정합니다. 기본값은 0입니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| virtual [Clone](../../groupdocs.signature.domain.extensions/signatureextension/clone)() | 이 개체의 복사본을 가져옵니다. |

### 또한보십시오

* class [SignatureExtension](../signatureextension)
* 네임스페이스 [GroupDocs.Signature.Domain.Extensions](../../groupdocs.signature.domain.extensions)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->