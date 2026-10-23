---
title: "konstruktor __init__"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Menginisialisasi PdfTextFormFieldSignature dengan nama yang telah ditentukan."
type: docs
url: /id/python-net/groupdocs.signature.domain/textformfieldsignature/__init__/
is_root: false
weight: 10
---


## __init__ {#name}

Menginisialisasi PdfTextFormFieldSignature dengan nama yang telah ditentukan.

```python
def __init__(self, name):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama objek field formulir. |

### Contoh

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

Menginisialisasi PdfTextFormFieldSignature dengan nama yang telah ditentukan.

```python
def __init__(self, name, text):
    ...
```

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| name | `str` | Nama objek field formulir. |
| text | `str` | Teks objek bidang formulir. |

### Contoh

```python
from groupdocs.signature.domain import TextFormFieldSignature

# Buat bidang formulir teks bernama "FieldText" dengan nilai "Value1"
text_field = TextFormFieldSignature("FieldText", "Value1")
```

### Lihat Juga
* class [`TextFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/textformfieldsignature/)
