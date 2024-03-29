---
title: GetData
second_title: .NET API 참조용 GroupDocs.Signature
description: 역직렬화를 통해 메타데이터 서명 값에서 개체를 가져옵니다.
type: docs
weight: 70
url: /ko/net/groupdocs.signature.domain/metadatasignature/getdata/
---
## GetData&lt;T&gt;() {#getdata}

역직렬화를 통해 메타데이터 서명 값에서 개체를 가져옵니다.

```csharp
public T GetData<T>()
    where T : class
```

| 모수 | 설명 |
| --- | --- |
| T | 메타데이터 값에서 역직렬화할 객체 유형 |

### 반환 값

T 개체의 인스턴스

### 또한보십시오

* class [MetadataSignature](../../metadatasignature)
* 네임스페이스 [GroupDocs.Signature.Domain](../../metadatasignature)
* 집회 [GroupDocs.Signature](../../../)

---

## GetData&lt;T&gt;(IDataEncryption) {#getdata_1}

역직렬화를 통해 메타데이터 서명 텍스트에서 개체를 가져옵니다.

```csharp
public T GetData<T>(IDataEncryption dataEncryption)
    where T : class
```

| 모수 | 설명 |
| --- | --- |
| T | 메타데이터 값에서 역직렬화할 객체 유형 |
| dataEncryption | 사용자 지정 데이터 암호화 구현 설정 |

### 또한보십시오

* interface [IDataEncryption](../../../groupdocs.signature.domain.extensions/idataencryption)
* class [MetadataSignature](../../metadatasignature)
* 네임스페이스 [GroupDocs.Signature.Domain](../../metadatasignature)
* 집회 [GroupDocs.Signature](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for GroupDocs.Signature.dll -->
