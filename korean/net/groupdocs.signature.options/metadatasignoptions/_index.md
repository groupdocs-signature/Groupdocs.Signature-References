---
title: MetadataSignOptions
second_title: .NET API 참조용 GroupDocs.Signature
description: 메타데이터 서명 옵션을 나타냅니다.
type: docs
weight: 1490
url: /ko/net/groupdocs.signature.options/metadatasignoptions/
---
## MetadataSignOptions class

메타데이터 서명 옵션을 나타냅니다.

```csharp
public class MetadataSignOptions : SignOptions
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [MetadataSignOptions](metadatasignoptions#constructor)() | 기본값을 사용하여 MetadataSignOptions 클래스의 새 인스턴스를 초기화합니다. |
| [MetadataSignOptions](metadatasignoptions#constructor_1)(IEnumerable&lt;MetadataSignature&gt;) | Metadata. 를 사용하여 MetadataSignOptions 클래스의 새 인스턴스를 초기화합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| virtual [AllPages](../../groupdocs.signature.options/signoptions/allpages) { get; set; } | 모든 문서 페이지에 서명하십시오. |
| [Appearance](../../groupdocs.signature.options/signoptions/appearance) { get; set; } | 시그니처 추가 등장. |
| [DataEncryption](../../groupdocs.signature.options/metadatasignoptions/dataencryption) { get; set; } | 구현을 가져오거나 설정합니다.[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption)이 옵션 컬렉션으로 모든 메타데이터 서명을 암호화하기 위한 인터페이스. 이 값이 설정되면 추가된 모든 서명은 기본적으로 이 암호화를 사용하거나 할당된 경우 자체 DataEncryption을 사용합니다. |
| [DocumentType](../../groupdocs.signature.options/signoptions/documenttype) { get; set; } | 서명 옵션의 문서 유형 가져오기 또는 설정[`DocumentType`](../../groupdocs.signature.domain/documenttype) |
| [Extensions](../../groupdocs.signature.options/signoptions/extensions) { get; } | 서명 확장. |
| virtual [PageNumber](../../groupdocs.signature.options/signoptions/pagenumber) { get; set; } | 서명할 문서 페이지 번호를 가져오거나 설정합니다. 최소 및 기본값은 1입니다. |
| virtual [PagesSetup](../../groupdocs.signature.options/signoptions/pagessetup) { get; set; } | 서명할 페이지를 지정하는 옵션입니다. |
| [Signatures](../../groupdocs.signature.options/metadatasignoptions/signatures) { get; set; } | 서명의 메타데이터를 가져오거나 설정합니다. |
| [SignatureType](../../groupdocs.signature.options/signoptions/signaturetype) { get; } | 서명 유형 가져오기[`SignatureType`](../../groupdocs.signature.domain/signaturetype) |
| [ZOrder](../../groupdocs.signature.options/signoptions/zorder) { get; set; } | 텍스트 서명의 Z 순서 위치를 가져오거나 설정합니다. 겹치는 서명의 표시 순서를 결정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| [Add](../../groupdocs.signature.options/metadatasignoptions/add)(MetadataSignature) | 컬렉션에 기존 MetadataSignature 인스턴스를 추가합니다. |
| [AddImageSignature](../../groupdocs.signature.options/metadatasignoptions/addimagesignature)(ushort, object) | 전달된 인수로 새 ImageMetadataSignature를 만들고 컬렉션에 추가합니다. |
| [AddPdfSignature](../../groupdocs.signature.options/metadatasignoptions/addpdfsignature)(string, object, string) | 전달된 인수로 새 PdfMetadataSignature를 만들고 컬렉션에 추가합니다. |

### 비고

**더 알아보기**

* GroupDocs.Signature에 의한 메타데이터 전자 서명 생성의 기본 사용법: [메타데이터 서명으로 문서에 전자 서명하는 방법](https://docs.groupdocs.com/display/signaturenet/eSign+document+with+Metadata+signature)
* GroupDocs.Signature를 사용한 메타데이터 전자 서명 설정의 고급 사용: [메타데이터 서명 및 추가 설정을 사용하여 문서에 전자 서명하기 위한 고급 사용](https://docs.groupdocs.com/display/signaturenet/Sign+document+with+Metadata+signature+-+advanced)

### 또한보십시오

* class [SignOptions](../signoptions)
* 네임스페이스 [GroupDocs.Signature.Options](../../groupdocs.signature.options)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
