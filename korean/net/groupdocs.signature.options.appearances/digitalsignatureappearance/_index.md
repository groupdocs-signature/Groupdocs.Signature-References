---
title: DigitalSignatureAppearance
second_title: .NET API 참조용 GroupDocs.Signature
description: 디지털 서명용 서명란의 모양을 설명합니다. 하나의 서명란은 하나의 디지털 서명에만 적용될 수 있습니다. 서명란은 항상 첫 페이지에 있습니다. 이 기능은 .docx .doc .odt 및 .xlsx 파일 형식에 유용할 수 있습니다.
type: docs
weight: 1190
url: /ko/net/groupdocs.signature.options.appearances/digitalsignatureappearance/
---
## DigitalSignatureAppearance class

디지털 서명용 서명란의 모양을 설명합니다. 하나의 서명란은 하나의 디지털 서명에만 적용될 수 있습니다. 서명란은 항상 첫 페이지에 있습니다. 이 기능은 .docx, .doc, .odt 및 .xlsx 파일 형식에 유용할 수 있습니다.

```csharp
public sealed class DigitalSignatureAppearance : SignatureAppearance
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [DigitalSignatureAppearance](digitalsignatureappearance#constructor)() | 서명란 모양 객체를 생성합니다. |
| [DigitalSignatureAppearance](digitalsignatureappearance#constructor_1)(string, string, string) | 지정된 값(서명자, 제목, 이메일)으로 서명란 모양을 만듭니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [Email](../../groupdocs.signature.options.appearances/digitalsignatureappearance/email) { get; set; } | 서명란에 표시될 이메일을 가져오거나 설정합니다. |
| [Signer](../../groupdocs.signature.options.appearances/digitalsignatureappearance/signer) { get; set; } | 서명란의 서명자 이름을 가져오거나 설정합니다. |
| [Title](../../groupdocs.signature.options.appearances/digitalsignatureappearance/title) { get; set; } | 서명란의 제목을 가져오거나 설정합니다. |

### 또한보십시오

* class [SignatureAppearance](../signatureappearance)
* 네임스페이스 [GroupDocs.Signature.Options.Appearances](../../groupdocs.signature.options.appearances)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->