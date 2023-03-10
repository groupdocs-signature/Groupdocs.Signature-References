---
title: PreviewOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: PreviewOptions 개체를 초기화합니다.
type: docs
weight: 10
url: /ko/net/groupdocs.signature.options/previewoptions/previewoptions/
---
## PreviewOptions(CreatePageStream, params int[]) {#constructor_1}

PreviewOptions 개체를 초기화합니다.

```csharp
public PreviewOptions(CreatePageStream createPageStream, params int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 미리보기 스트림을 생성하는 방법을 정의하는 대리자입니다. |
| pageNumbers | Int32[] | 원하는 페이지 번호 |

### 또한보십시오

* delegate [CreatePageStream](../../createpagestream)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../previewoptions)
* 집회 [GroupDocs.Signature](../../../)

---

## PreviewOptions(CreatePageStream, ReleasePageStream, params int[]) {#constructor}

PreviewOptions 개체를 초기화합니다.

```csharp
public PreviewOptions(CreatePageStream createPageStream, ReleasePageStream releasePageStream, 
    params int[] pageNumbers)
```

| 모수 | 유형 | 설명 |
| --- | --- | --- |
| createPageStream | CreatePageStream | 출력 페이지 미리보기 스트림을 생성하는 방법을 정의하는 대리자입니다. |
| releasePageStream | ReleasePageStream | 출력 페이지 미리보기 스트림을 해제하는 방법을 정의하는 대리자입니다. |
| pageNumbers | Int32[] | 원하는 페이지 번호 |

### 또한보십시오

* delegate [CreatePageStream](../../createpagestream)
* delegate [ReleasePageStream](../../releasepagestream)
* class [PreviewOptions](../../previewoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../previewoptions)
* 집회 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->