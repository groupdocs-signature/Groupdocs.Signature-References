---
title: "add 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "기존 MetadataSignature 인스턴스를 컬렉션에 추가합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

기존 MetadataSignature 인스턴스를 컬렉션에 추가합니다.

```python
def add(self, metadata_signature):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | 추가될 기존 MetadataSignature 인스턴스입니다. |

**Returns:** The MetadataSignOptions instance.

### 예시

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### 또 보기
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
