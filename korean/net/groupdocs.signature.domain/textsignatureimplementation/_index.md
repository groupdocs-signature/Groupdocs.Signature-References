---
title: TextSignatureImplementation
second_title: .NET API 참조용 GroupDocs.Signature
description: PDF 텍스트 서명에 대한 구현 유형을 지정합니다.
type: docs
weight: 1010
url: /ko/net/groupdocs.signature.domain/textsignatureimplementation/
---
## TextSignatureImplementation enumeration

PDF 텍스트 서명에 대한 구현 유형을 지정합니다.

```csharp
public enum TextSignatureImplementation
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Native | `1` | 문서 페이지의 기본 텍스트 개체로서의 텍스트 서명. |
| Image | `2` | 문서 페이지의 이미지 개체로 텍스트 서명. |
| Annotation | `3` | PDF 페이지의 텍스트 주석 개체로서의 텍스트 서명. 라이센스 버전에서만 주석을 볼 수 있습니다. |
| Sticker | `4` | PDF 페이지의 스티커 개체로 텍스트 서명. |
| FormField | `5` | 지정된 양식 필드의 텍스트로 텍스트 서명. 이 구현 유형에서는 TextSignOptions.Text, TextSignOptions.FormTextFieldType 및 TextSignOptions.FormTextFieldTitle 옵션만 사용할 수 있습니다. |
| Watermark | `6` | 문서 페이지의 워터마크로 텍스트 서명. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->