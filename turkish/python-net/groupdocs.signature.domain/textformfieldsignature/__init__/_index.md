---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Önceden tanımlı bir adla PdfTextFormFieldSignature başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Önceden tanımlı bir adla PdfTextFormFieldSignature başlatır.

```python
def __init__(self, name):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Form alanı nesnesinin adı. |

### Örnek

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

Önceden tanımlı bir adla PdfTextFormFieldSignature başlatır.

```python
def __init__(self, name, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| name | `str` | Form alanı nesnesinin adı. |
| text | `str` | Form alanı nesnesinin metni. |

### Örnek

```python
from groupdocs.signature.domain import TextFormFieldSignature

# "FieldText" adında bir metin form alanı oluştur ve "Value1" değerini ata
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Ayrıca Bakınız
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
