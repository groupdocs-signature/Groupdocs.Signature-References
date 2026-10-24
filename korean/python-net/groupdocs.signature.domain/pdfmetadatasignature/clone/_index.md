---
title: "clone 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "Metadata Signature 인스턴스를 복제합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Metadata Signature 인스턴스를 복제합니다.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### 예시

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # 새 값을 사용하여 표준 메타데이터 서명을 복제합니다
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

주어진 값을 사용하여 PDF 메타데이터 서명 인스턴스를 복제합니다.

```python
def clone(self, value):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| value | `Any` | 새로 복제된 객체의 값. |

**Returns:** A cloned metadata signature instance.

### 예시

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# 새 값을 사용하여 기존 메타데이터 서명을 복제합니다
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### 또 보기
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
