---
title: "clone 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "메타데이터 서명 인스턴스를 복제합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

메타데이터 서명 인스턴스를 복제합니다.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### 예시

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 미리 정의된 AUTHOR 서명을 기반으로 새로운 메타데이터 서명을 생성합니다.
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

주어진 값으로 메타데이터 서명 인스턴스를 복제합니다.

```python
def clone(self, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| value | `Any` | 새로 복제된 객체의 값. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### 예시

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 새 값을 사용하여 기존 메타데이터 서명을 복제합니다
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 또 보기
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
