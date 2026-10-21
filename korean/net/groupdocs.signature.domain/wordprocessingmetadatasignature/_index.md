---
title: "WordProcessingMetadataSignature"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "워드 프로세싱 메타데이터 서명 속성을 포함합니다."
type: docs
weight: 1260
url: /ko/net/groupdocs.signature.domain/wordprocessingmetadatasignature/
---
## WordProcessingMetadataSignature class

워드 프로세싱 메타데이터 서명 속성을 포함합니다.

```csharp
public sealed class WordProcessingMetadataSignature : MetadataSignature
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor)(string) | 미리 정의된 이름과 빈 값으로 WordProcessing Metadata Signature를 생성합니다. |
| [WordProcessingMetadataSignature](wordprocessingmetadatasignature#constructor_1)(string, object) | 미리 정의된 값들로 WordProcessing Metadata Signature를 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 서명 생성 날짜를 가져오거나 설정합니다. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | 서명 Value 속성을 인코딩 및 디코딩하기 위해 [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그를 가져옵니다. 이 속성은 삭제된 서명의 목록을 유지하기 위한 문서 기록 로그 레코드에만 사용됩니다. |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 서명의 높이를 지정합니다. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다. 이 속성은 Update 메서드와 함께 사용되어 요소를 서명(true) 또는 문서 요소(false)로 설정합니다. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 서명의 왼쪽 위치를 지정합니다. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 서명 수정 날짜를 가져오거나 설정합니다. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 고유 메타데이터 이름을 지정합니다. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 서명이 발견된 페이지를 지정합니다. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Update 또는 Delete 메서드를 통해 문서에서 서명을 수정하기 위한 고유 서명 식별자입니다. 이 속성은 Sign 또는 Search 메서드가 호출된 후 자동으로 설정됩니다. 이전에 저장된 경우 서명을 조작하기 위해 수동으로 설정할 수 있습니다. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 서명의 유형을 지정합니다. |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 서명의 상단 위치를 지정합니다. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | 메타데이터 값 유형을 지정합니다. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | 메타데이터 객체를 지정합니다. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 서명의 너비를 지정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone_1)() | 메타데이터 서명 인스턴스를 복제합니다. |
| override [Clone](../../groupdocs.signature.domain/wordprocessingmetadatasignature/clone#clone)(object) | 주어진 값으로 Words Metadata Signature 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.signature.domain/metadatasignature/equals)(object) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | 역직렬화를 통해 메타데이터 서명 Value에서 객체를 얻습니다. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | 역직렬화를 통해 메타데이터 서명 텍스트에서 객체를 얻습니다. |
| override [GetHashCode](../../groupdocs.signature.domain/metadatasignature/gethashcode)() | GetHashCode 메서드를 재정의합니다 |
| virtual [ToBoolean](../../groupdocs.signature.domain/metadatasignature/toboolean)() | 불리언으로 변환합니다 |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)() | DateTime으로 변환합니다. |
| virtual [ToDateTime](../../groupdocs.signature.domain/metadatasignature/todatetime)(IFormatProvider) | DateTime으로 변환합니다. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)() | Decimal로 변환합니다. |
| virtual [ToDecimal](../../groupdocs.signature.domain/metadatasignature/todecimal)(IFormatProvider) | Decimal로 변환합니다. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)() | Double로 변환합니다. |
| virtual [ToDouble](../../groupdocs.signature.domain/metadatasignature/todouble)(IFormatProvider) | Double로 변환합니다. |
| virtual [ToInteger](../../groupdocs.signature.domain/metadatasignature/tointeger)() | integer로 변환합니다. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)() | float으로 변환합니다. |
| virtual [ToSingle](../../groupdocs.signature.domain/metadatasignature/tosingle)(IFormatProvider) | float으로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring)() | String으로 변환하며 ToString() 메서드를 재정의합니다. |
| virtual [ToString](../../groupdocs.signature.domain/metadatasignature/tostring)(string) | 지정된 형식으로 String으로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/wordprocessingmetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 지정된 형식으로 String으로 변환합니다. |

### 또 보기

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
