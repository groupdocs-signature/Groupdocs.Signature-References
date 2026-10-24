---
title: "clone 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "FormField 서명 인스턴스를 복제합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField 서명 인스턴스를 복제합니다.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### 예시

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 새 값을 사용하여 메타데이터 서명을 복제합니다.
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 또 보기
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
