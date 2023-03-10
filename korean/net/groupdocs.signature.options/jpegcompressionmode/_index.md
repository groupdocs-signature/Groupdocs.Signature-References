---
title: JpegCompressionMode
second_title: .NET API 참조용 GroupDocs.Signature
description: JPEG 압축 모드를 지정합니다.
type: docs
weight: 1440
url: /ko/net/groupdocs.signature.options/jpegcompressionmode/
---
## JpegCompressionMode enumeration

JPEG 압축 모드를 지정합니다.

```csharp
public enum JpegCompressionMode
```

### 가치

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Baseline | `0` | 기본 압축. |
| Progressive | `1` | 점진적 압축. |
| Lossless | `2` | 무손실 압축. 많은 이미지 뷰어가 지원하지 않기 때문에 이 압축 유형을 신중하게 사용하십시오. 사용하는 경우 를 할당해 보십시오.[`ColorType`](../jpegsaveoptions/colortype) 재산Grayscale 또는Rgb 가치. |
| JpegLs | `3` | JPEG-LS 압축. 많은 이미지 뷰어가 지원하지 않기 때문에 이 압축 유형을 신중하게 사용하십시오. 사용하는 경우 를 할당해 보십시오.[`ColorType`](../jpegsaveoptions/colortype) 재산Grayscale 값. |

### 또한보십시오

* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->