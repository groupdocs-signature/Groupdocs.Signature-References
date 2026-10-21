---
title: "ImageMetadataSignature"
second_title: "GroupDocs.Signature for .NET API 참조"
description: "이미지 메타데이터 서명 속성을 포함합니다."
type: docs
weight: 740
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
| [ImageMetadataSignature](imagemetadatasignature)(ushort, object) | Id와 값을 사용하여 Image Metadata Signature를 생성합니다 |

## 속성

| 이름 | 설명 |
| --- | --- |
| [CreatedOn](../../groupdocs.signature.domain/basesignature/createdon) { get; set; } | 서명 생성 날짜를 가져오거나 설정합니다. |
| [DataEncryption](../../groupdocs.signature.domain/metadatasignature/dataencryption) { get; set; } | 서명 Value 속성을 인코딩 및 디코딩하기 위해 [`IDataEncryption`](../../groupdocs.signature.domain.extensions/idataencryption) 인터페이스의 구현을 가져오거나 설정합니다. |
| [Deleted](../../groupdocs.signature.domain/basesignature/deleted) { get; } | 이 서명이 문서에서 삭제되었는지 여부를 나타내는 플래그를 가져옵니다. 이 속성은 삭제된 서명의 목록을 유지하기 위한 문서 기록 로그 레코드에만 사용됩니다. |
| [Description](../../groupdocs.signature.domain/imagemetadatasignature/description) { get; } | 표준 Image Metadata 서명의 설명을 가져오기 위한 읽기 전용 값 |
| [Height](../../groupdocs.signature.domain/basesignature/height) { get; set; } | 서명의 높이를 지정합니다. |
| [Id](../../groupdocs.signature.domain/imagemetadatasignature/id) { get; set; } | Image Metadata 서명의 식별자입니다. 표준 Signature와 미리 정의된 Id 값을 포함하는 ImageMetadataSignatures 클래스를 참조하십시오. |
| [IsSignature](../../groupdocs.signature.domain/basesignature/issignature) { get; set; } | 이 구성 요소가 서명인지 문서 내용인지 표시하는 플래그를 가져오거나 설정합니다. 이 속성은 Update 메서드와 함께 사용되어 요소를 서명(true) 또는 문서 요소(false)로 설정합니다. |
| [Left](../../groupdocs.signature.domain/basesignature/left) { get; set; } | 서명의 왼쪽 위치를 지정합니다. |
| [ModifiedOn](../../groupdocs.signature.domain/basesignature/modifiedon) { get; set; } | 서명 수정 날짜를 가져오거나 설정합니다. |
| [Name](../../groupdocs.signature.domain/metadatasignature/name) { get; set; } | 고유 메타데이터 이름을 지정합니다. |
| [PageNumber](../../groupdocs.signature.domain/basesignature/pagenumber) { get; } | 서명이 발견된 페이지를 지정합니다. |
| [SignatureId](../../groupdocs.signature.domain/basesignature/signatureid) { get; } | Update 또는 Delete 메서드를 통해 문서에서 서명을 수정하기 위한 고유 서명 식별자입니다. 이 속성은 Sign 또는 Search 메서드가 호출된 후 자동으로 설정됩니다. 이전에 저장된 경우 서명을 조작하기 위해 수동으로 설정할 수 있습니다. |
| [SignatureType](../../groupdocs.signature.domain/basesignature/signaturetype) { get; } | 서명의 유형을 지정합니다. |
| [Size](../../groupdocs.signature.domain/imagemetadatasignature/size) { get; } | Metadata 값의 크기를 가져오기 위한 읽기 전용 값 |
| [Top](../../groupdocs.signature.domain/basesignature/top) { get; set; } | 서명의 상단 위치를 지정합니다. |
| [Type](../../groupdocs.signature.domain/metadatasignature/type) { get; } | 메타데이터 값 유형을 지정합니다. |
| [Value](../../groupdocs.signature.domain/metadatasignature/value) { get; set; } | 메타데이터 객체를 지정합니다. |
| [Width](../../groupdocs.signature.domain/basesignature/width) { get; set; } | 서명의 너비를 지정합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone_1)() | 메타데이터 서명 인스턴스를 복제합니다. |
| override [Clone](../../groupdocs.signature.domain/imagemetadatasignature/clone#clone)(object) | 주어진 값으로 Image Metadata Signature 인스턴스를 복제합니다. |
| override [Equals](../../groupdocs.signature.domain/imagemetadatasignature/equals)(object) | 서명 속성을 비교하기 위해 Equals 메서드를 재정의합니다 |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)() | 역직렬화를 통해 메타데이터 서명 Value에서 객체를 얻습니다. |
| [GetData&lt;T&gt;](../../groupdocs.signature.domain/metadatasignature/getdata)(IDataEncryption) | 역직렬화를 통해 메타데이터 서명 텍스트에서 객체를 얻습니다. |
| override [GetHashCode](../../groupdocs.signature.domain/imagemetadatasignature/gethashcode)() | GetHashCode 메서드를 재정의합니다 |
| override [ToBoolean](../../groupdocs.signature.domain/imagemetadatasignature/toboolean)() | 불리언으로 변환합니다 |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime)() | DateTime으로 변환합니다. |
| override [ToDateTime](../../groupdocs.signature.domain/imagemetadatasignature/todatetime#todatetime_1)(IFormatProvider) | DateTime으로 변환합니다. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal)() | Decimal로 변환합니다. |
| override [ToDecimal](../../groupdocs.signature.domain/imagemetadatasignature/todecimal#todecimal_1)(IFormatProvider) | Decimal로 변환합니다. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble)() | Double로 변환합니다. |
| override [ToDouble](../../groupdocs.signature.domain/imagemetadatasignature/todouble#todouble_1)(IFormatProvider) | Double로 변환합니다. |
| override [ToInteger](../../groupdocs.signature.domain/imagemetadatasignature/tointeger)() | integer로 변환합니다. |
| [ToLong](../../groupdocs.signature.domain/imagemetadatasignature/tolong)() | long 형식으로 변환합니다. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle)() | float으로 변환합니다. |
| override [ToSingle](../../groupdocs.signature.domain/imagemetadatasignature/tosingle#tosingle_1)(IFormatProvider) | float으로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring)() | String으로 변환하며 ToString() 메서드를 재정의합니다. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_1)(string) | 지정된 형식으로 String으로 변환합니다. |
| override [ToString](../../groupdocs.signature.domain/imagemetadatasignature/tostring#tostring_2)(string, IFormatProvider) | 지정된 형식으로 String으로 변환합니다. |

### 또 보기

* class [MetadataSignature](../metadatasignature)
* namespace [GroupDocs.Signature.Domain](../../groupdocs.signature.domain)
* assembly [GroupDocs.Signature](../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.signature.dll -->
