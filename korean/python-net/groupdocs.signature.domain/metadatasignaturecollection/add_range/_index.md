---
title: "add_range 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명 컬렉션을 추가합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/metadatasignaturecollection/add_range/
is_root: false
weight: 1030
---


## add_range {#signatures}

메타데이터 서명 컬렉션을 추가합니다.

```python
def add_range(self, signatures):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signatures | `Iterable[MetadataSignature]` | 추가할 서명의 컬렉션. |

### 예시

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import WordProcessingMetadataSignature

def sign_docx():
    with Signature("sample.docx") as signature:
        options = MetadataSignOptions()
        signatures = [
            WordProcessingMetadataSignature("Author", "Mr.Scherlock Holmes"),
            WordProcessingMetadataSignature("DateCreated", datetime.now()),
            WordProcessingMetadataSignature("DocumentId", 123456),
            WordProcessingMetadataSignature("SignatureId", 123.456),
        ]
        options.signatures.add_range(signatures)
        result = signature.sign("signed.docx", options)
        print(f"Signed with {len(result.succeeded)} metadata signature(s):")
        for item in result.succeeded:
            print(f"  {item.name}")
```

### 또 보기
* class [`MetadataSignatureCollection`](/signature/python-net/groupdocs.signature.domain/metadatasignaturecollection/)
