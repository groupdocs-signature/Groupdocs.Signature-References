---
title: "clone 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "이 객체의 복사본을 가져옵니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

이 객체의 복사본을 가져옵니다.

```python
def clone(self):
    ...
```

### 예시

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # 새 값을 사용하여 메타데이터 서명을 복제합니다.
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### 또 보기
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
