---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "미리 정의된 이름과 빈 값을 사용하여 PDF 메타데이터 서명을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/pdfmetadatasignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

미리 정의된 이름과 빈 값을 사용하여 PDF 메타데이터 서명을 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | PDF 메타데이터 서명 이름. |

## __init__ {#name-value}

미리 정의된 값으로 PDF 메타데이터 서명을 초기화합니다.

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
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr. Sherlock Holmes"))
    options.add(PdfMetadataSignature("CreatedOn", datetime.now()))
    options.add(PdfMetadataSignature("DocumentId", 123456))
    options.add(PdfMetadataSignature("SignatureId", 123.456))
    result = signature.sign("signed.pdf", options)
```

## __init__ {#name-value-tag}

미리 정의된 값으로 PDF 메타데이터 서명을 초기화합니다.

```python
def __init__(self, name, value, tag):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 메타데이터 서명 객체의 이름. |
| value | `Any` | 메타데이터 서명의 값. |
| tag | `str` | 메타데이터 서명의 접두사 태그. |

### 예시

```python
from groupdocs.signature.domain import PdfMetadataSignature

# PDF 작성자를 위한 메타데이터 서명을 생성합니다
author_sig = PdfMetadataSignature("Author", "Mr. Sherlock Holmes")

# 생성 날짜를 위한 메타데이터 서명을 생성합니다
from datetime import datetime
created_sig = PdfMetadataSignature("CreatedOn", datetime.now())

# 숫자 식별자를 위한 메타데이터 서명을 생성합니다
id_sig = PdfMetadataSignature("DocumentId", 123456)

# 부동 소수점 값을 위한 메타데이터 서명을 생성합니다
float_sig = PdfMetadataSignature("SignatureId", 123.456)
```

### 또 보기
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
