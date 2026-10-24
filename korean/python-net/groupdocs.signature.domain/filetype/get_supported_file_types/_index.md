---
title: "get_supported_file_types 메서드"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "지원되는 파일 유형을 검색합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/filetype/get_supported_file_types/
is_root: false
weight: 1060
---


## get_supported_file_types

지원되는 파일 유형을 검색합니다.

```python
def get_supported_file_types(cls):
    ...
```

**Returns:** Iterable of supported `FileType` objects.

### 예시

```python
import os
from groupdocs.signature.domain import FileType

for file_type in FileType.get_supported_file_types():
    print(f"{file_type.extension}: {file_type.file_format}")
```

### 또 보기
* class [`FileType`](/signature/python-net/groupdocs.signature.domain/filetype/)
