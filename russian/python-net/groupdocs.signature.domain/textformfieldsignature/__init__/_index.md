---
title: "__init__ конструктор"
second_title: "GroupDocs.Signature for Python via .NET Справочник API"
description: "Инициализирует PdfTextFormFieldSignature с предопределённым именем."
type: docs
url: /ru/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Инициализирует PdfTextFormFieldSignature с предопределённым именем.

```python
def __init__(self, name):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя объекта поля формы. |

### Пример

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

Инициализирует PdfTextFormFieldSignature с предопределённым именем.

```python
def __init__(self, name, text):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| name | `str` | Имя объекта поля формы. |
| text | `str` | Текст объекта поля формы. |

### Пример

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Создайте текстовое поле формы с именем "FieldText" и значением "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### См. также
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
