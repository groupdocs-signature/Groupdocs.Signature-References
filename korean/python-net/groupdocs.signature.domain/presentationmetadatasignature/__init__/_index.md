---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 이름과 빈 값을 사용하여 PresentationMetadataSignature를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/presentationmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

지정된 이름과 빈 값을 사용하여 PresentationMetadataSignature를 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | Presentation Metadata Signature 이름. |

## __init__ {#name-value}

미리 정의된 값을 사용하여 PresentationMetadataSignature를 초기화합니다.

```python
def __init__(self, name, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 메타데이터 서명 객체의 이름. |
| value | `Any` | 메타데이터 서명의 값. |

### 예시

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PresentationMetadataSignature

with Signature("sample.ppsx") as signature:
    options = MetadataSignOptions()
    signatures = [
        PresentationMetadataSignature("Author", "Mr. Sherlock Holmes"),
        PresentationMetadataSignature("DateCreated", datetime.now()),
        PresentationMetadataSignature("DocumentId", 123456),
        PresentationMetadataSignature("SignatureId", 123.456),
    ]
    options.signatures.add_range(signatures)
    result = signature.sign("signed.ppsx", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s):")
    for item in result.succeeded:
        print(f"  {item.name}")
```

### 또 보기
* class [`PresentationMetadataSignature`](/signature/python-net/groupdocs.signature.domain/presentationmetadatasignature/)
