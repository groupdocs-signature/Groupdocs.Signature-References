---
title: "clone 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "FormField 서명 인스턴스를 복제합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/comboboxformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField 서명 인스턴스를 복제합니다.

```python
def clone(self):
    ...
```

**Returns:** A cloned FormField signature instance.

### 예시

```python
from groupdocs.signature.domain import ComboboxFormFieldSignature

# 원본 콤보박스 폼 필드 서명을 생성합니다
original = ComboboxFormFieldSignature()

# 서명을 복제합니다
cloned = original.clone()
```

### 또 보기
* class [`ComboboxFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/comboboxformfieldsignature/)
