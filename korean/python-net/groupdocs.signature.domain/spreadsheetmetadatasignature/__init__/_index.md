---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "미리 정의된 이름과 빈 값을 사용하여 Spreadsheet Metadata Signature를 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

미리 정의된 이름과 빈 값을 사용하여 Spreadsheet Metadata Signature를 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 스프레드시트 메타데이터 서명 이름. |

## __init__ {#name-value}

미리 정의된 값으로 Spreadsheet Metadata Signature를 초기화합니다.

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
from groupdocs.signature.domain import SpreadsheetMetadataSignature

# 스프레드시트에 대한 메타데이터 서명을 생성합니다
author_sig = SpreadsheetMetadataSignature("Author", "Mr. Sherlock Holmes")
date_sig = SpreadsheetMetadataSignature("DateCreated", datetime.now())
id_sig = SpreadsheetMetadataSignature("DocumentId", 123456)
float_sig = SpreadsheetMetadataSignature("SignatureId", 123.456)
```

### 또 보기
* class [`SpreadsheetMetadataSignature`](/signature/python-net/groupdocs.signature.domain/spreadsheetmetadatasignature/)
