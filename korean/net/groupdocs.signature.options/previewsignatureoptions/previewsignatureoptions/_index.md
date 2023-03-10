---
title: PreviewSignatureOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: PreviewSignatureOptions 객체를 초기화합니다.
type: docs
weight: 10
url: /ko/net/groupdocs.signature.options/previewsignatureoptions/previewsignatureoptions/
---
## PreviewSignatureOptions(SignOptions, CreateSignatureStream) {#constructor}

PreviewSignatureOptions 객체를 초기화합니다.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, CreateSignatureStream createSignatureStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signOptions | SignOptions | 미리보기를 생성할 서명 옵션입니다. |
| createSignatureStream | CreateSignatureStream | 출력 서명 미리 보기 스트림을 생성하는 방법을 정의하는 대리자입니다. |

### 또한보십시오

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../previewsignatureoptions)
* 집회 [GroupDocs.Signature](../../../)

---

## PreviewSignatureOptions(SignOptions, CreateSignatureStream, ReleaseSignatureStream) {#constructor_1}

PreviewSignatureOptions 객체를 초기화합니다.

```csharp
public PreviewSignatureOptions(SignOptions signOptions, 
    CreateSignatureStream createSignatureStream, ReleaseSignatureStream releaseSignatureStream)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| signOptions | SignOptions | 미리보기를 생성할 서명 옵션입니다. |
| createSignatureStream | CreateSignatureStream | 출력 서명 미리 보기 스트림을 생성하는 방법을 정의하는 대리자입니다. |
| releaseSignatureStream | ReleaseSignatureStream | 출력 서명 미리 보기 스트림을 해제하는 방법을 정의하는 대리자입니다. |

### 또한보십시오

* class [SignOptions](../../signoptions)
* delegate [CreateSignatureStream](../../createsignaturestream)
* delegate [ReleaseSignatureStream](../../releasesignaturestream)
* class [PreviewSignatureOptions](../../previewsignatureoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../previewsignatureoptions)
* 집회 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->