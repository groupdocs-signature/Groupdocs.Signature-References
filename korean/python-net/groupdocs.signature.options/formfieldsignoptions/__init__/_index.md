---
title: "__init__ 생성자"
second_title: "GroupDocs.Signature Python용 .NET을 통한 API 참조"
description: "PdfFormFieldSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다."
type: docs
url: /ko/python-net/groupdocs.signature.options/formfieldsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

PdfFormFieldSignOptions 클래스의 새 인스턴스를 기본값으로 초기화합니다.

```python
def __init__(self):
    ...
```

### 예시

```python
from groupdocs.signature.options import FormFieldSignOptions
from groupdocs.signature.domain import TextFormFieldSignature

text_field = TextFormFieldSignature("FieldText", "Value1")
options = FormFieldSignOptions(text_field)
```

## __init__ {#signature}

PdfFormFieldSignOptions 클래스의 새 인스턴스를 FormField 서명으로 초기화합니다.

```python
def __init__(self, signature):
    ...
```

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| signature | `FormFieldSignature` | 양식 필드 서명 객체입니다. |

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

### 또 보기
* class [`FormFieldSignOptions`](/signature/python-net/groupdocs.signature.options/formfieldsignoptions/)
