---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "기본값으로 MetadataSearchOptions 클래스의 새 인스턴스를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

기본값으로 MetadataSearchOptions 클래스의 새 인스턴스를 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### 또 보기
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
