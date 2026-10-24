---
title: "get_document_info 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "문서 페이지에 대한 정보를 가져옵니다: 페이지 크기, 최대 페이지 높이, 최대 높이를 가진 페이지의 너비."
type: docs
url: /ko/python-net/groupdocs.signature/signature/get_document_info/
is_root: false
weight: 1130
---


## get_document_info

문서 페이지에 대한 정보를 가져옵니다: 페이지 크기, 최대 페이지 높이, 최대 높이를 가진 페이지의 너비.

서명된 문서에 대해 자세히 알아보세요 - 파일 유형, 페이지 수 및 기타 많은 형식별 속성:
- https://docs.groupdocs.com/display/signaturenet/Get+document+information

```python
def get_document_info(self):
    ...
```

**Returns:** Information about document.

### 예시

```python
from groupdocs.signature import Signature

with Signature("sample.pdf") as signature:
    info = signature.get_document_info()
    print(f"File type: {info.file_type.file_format}")
    print(f"Pages count: {info.page_count}")
    print(f"File size: {info.size} bytes")
    for page in info.pages:
        # page_number는 0부터 시작합니다: 0은 첫 번째 페이지입니다
        print(f"Page {page.page_number}: {page.width} x {page.height}")
```

### 또 보기
* class [`Signature`](/signature/python-net/groupdocs.signature/signature/)
