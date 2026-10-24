---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 식별자와 값으로 이미지 메타데이터 서명을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/imagemetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#id-value}

지정된 식별자와 값으로 이미지 메타데이터 서명을 초기화합니다.

```python
def __init__(self, id, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| id | `System.UInt16` | Image Metadata 서명의 고유 식별자. 가능한 id 값에 대한 EXIF 태그 사양은 참고 문서를 확인하십시오. |
| value | `Any` | 메타데이터 값. |

### 예시

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import ImageMetadataSignature

with Signature("sample.png") as signature:
    options = MetadataSignOptions()
    metadata_id = 41996
    options.add(ImageMetadataSignature(metadata_id, "Mr. Sherlock Holmes"))  # text
    options.add(ImageMetadataSignature(metadata_id + 1, datetime.now()))    # date and time
    options.add(ImageMetadataSignature(metadata_id + 2, 123456))            # integer
    options.add(ImageMetadataSignature(metadata_id + 3, 123.456))           # float
    result = signature.sign("signed.png", options)
```

### 또 보기
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
