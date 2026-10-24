---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지정된 이름과 빈 값을 사용하여 WordProcessingMetadataSignature를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

지정된 이름과 빈 값을 사용하여 WordProcessingMetadataSignature를 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | WordProcessing 메타데이터 서명 이름. |

### 예시

```python
from datetime import datetime
from groupdocs.signature.domain import WordProcessingMetadataSignature

# 이름과 값으로 메타데이터 서명을 생성합니다
author_sig = WordProcessingMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = WordProcessingMetadataSignature("DateCreated", datetime.now())
id_sig = WordProcessingMetadataSignature("DocumentId", 123456)
float_sig = WordProcessingMetadataSignature("SignatureId", 123.456)
```

## __init__ {#name-value}

미리 정의된 값으로 WordProcessing 메타데이터 서명을 초기화합니다.

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
from groupdocs.signature.domain import WordProcessingMetadataSignature

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
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
