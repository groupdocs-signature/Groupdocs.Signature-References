---
title: ImageMetadataSignature
second_title: .NET API 참조용 GroupDocs.Signature
description: 이미지 메타데이터 서명 속성을 포함합니다.
type: docs
weight: 570
url: /ko/net/groupdocs.signature.domain/imagemetadatasignature/
---
## ImageMetadataSignature class

이미지 메타데이터 서명 속성을 포함합니다.

```csharp
public sealed class ImageMetadataSignature : MetadataSignature
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | ID 및 value 를 사용하여 이미지 메타데이터 서명을 생성합니다. |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 서명 생성 날짜를 가져오거나 설정합니다. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | 구현을 가져오거나 설정합니다.[`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) 서명 값 속성을 인코딩 및 디코딩하는 인터페이스. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그를 가져옵니다. 이 속성은 삭제된 서명 목록을 유지하기 위해 문서 기록 로그 레코드에만 사용됩니다. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | 표준 이미지 메타데이터 signature 에 대한 설명을 가져오기 위한 읽기 전용 값 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 서명의 높이를 지정합니다. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | 이미지 메타데이터 서명의 식별자입니다. 참조ImageMetadataSignatures 미리 정의된 Id 값이 있는 표준 서명을 포함하는 클래스입니다. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 이 구성 요소가 서명 또는 문서 내용인지 나타내는 플래그를 가져오거나 설정합니다. 이 속성은 요소를 서명(true) 또는 문서 요소(false)로 설정하기 위해 Update 메서드와 함께 사용됩니다. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 서명의 왼쪽 위치를 지정합니다. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 서명 수정 날짜를 가져오거나 설정합니다. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 고유한 메타데이터 이름을 지정합니다. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 페이지 서명이 발견되었음을 지정합니다. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | 업데이트 또는 삭제 메서드를 통해 문서의 서명을 수정하는 고유한 서명 식별자입니다. 이 속성은 서명 또는 검색 메서드가 호출된 후 자동으로 설정됩니다. 서명을 조작하기 위해 수동으로 설정하기 전에 이 속성을 저장한 경우. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 서명 유형을 지정합니다. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | 메타데이터의 크기를 가져오는 읽기 전용 값 value |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 서명의 상단 위치를 지정합니다. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | 메타데이터 값 유형을 지정합니다. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | 메타데이터 개체를 지정합니다. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 서명의 너비를 지정합니다. |

## 행동 양식

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | 복제 메타데이터 서명 인스턴스. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | 주어진 값으로 이미지 메타데이터 서명 인스턴스 복제. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | 서명 속성을 비교하기 위해 Equals 메서드를 덮어씁니다 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | 역직렬화를 통해 메타데이터 서명 값에서 개체를 가져옵니다. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | 역직렬화를 통해 메타데이터 서명 텍스트에서 개체를 가져옵니다. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode method 재정의 |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | 부울로 변환합니다. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime으로 변환합니다. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime으로 변환합니다. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | 10진수로 변환합니다. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | 10진수로 변환합니다. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double로 변환합니다. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double로 변환합니다. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | 정수로 변환합니다. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | long. 로 변환 |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float로 변환합니다. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | 재정의를 통해 문자열로 변환 ToString() method |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | 지정된 format 의 문자열로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 지정된 format 의 문자열로 변환합니다. |

### 또한보십시오

* class [MetadataSignature](../metadatasignature)
* 네임스페이스 [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* 집회 [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
