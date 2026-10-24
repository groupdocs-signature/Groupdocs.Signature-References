---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "미리 정의된 이름으로 PdfTextFormFieldSignature을 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

미리 정의된 이름으로 PdfTextFormFieldSignature을 초기화합니다.

```python
def __init__(self, name):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 폼 필드 객체의 이름. |

### 예시

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

with Signature("sample.pdf") as signature:
    text_field = TextFormFieldSignature("FieldText", "Value1")
    options = FormFieldSignOptions(text_field)
    options.left = 100
    options.top = 400
    options.width = 200
    options.height = 20
    result = signature.sign("signed_form_field.pdf", options)
    for field in result.succeeded:
        print(f"Added form field '{field.name}' with value '{field.value}'")
```

## __init__ {#name-text}

미리 정의된 이름으로 PdfTextFormFieldSignature을 초기화합니다.

```python
def __init__(self, name, text):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| name | `str` | 폼 필드 객체의 이름. |
| text | `str` | 폼 필드 객체의 텍스트. |

### 예시

```python
from groupdocs.signature.domain import TextFormFieldSignature

# 값 "Value1"을 가진 "FieldText"라는 텍스트 폼 필드를 생성합니다.
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### 또 보기
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
