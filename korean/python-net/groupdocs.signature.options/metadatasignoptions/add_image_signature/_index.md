---
title: "add_image_signature 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "주어진 인수를 사용하여 새 ImageMetadataSignature를 생성하고 컬렉션에 추가합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasignoptions/add_image_signature/
is_root: false
weight: 1020
---


## add_image_signature {#id-value}

주어진 인수를 사용하여 새 ImageMetadataSignature를 생성하고 컬렉션에 추가합니다.

```python
def add_image_signature(self, id, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata Signature 이름에 대한 고유 식별자입니다. 가능한 ID 값에 대한 Exif 태그 사양은 참고 문서를 확인하십시오. |
| value | `Any` | 메타데이터 값. |

**Returns:** ImageMetadataSignature: The newly created signature that was added to the MetadataSignatures collection.

### 또 보기
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
