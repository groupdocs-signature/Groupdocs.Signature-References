---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/textsearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

TextSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import TextSearchOptions

with Signature("signed.pdf") as signature:
    # Varsayılan seçenekleri kullanarak metin imzalarını ara
    result = signature.search([TextSearchOptions()])
    for text_signature in result.signatures:
        print(f"Found text signature: {text_signature.text}")
```

## __init__ {#text}

TextSearchOptions sınıfının yeni bir örneğini bir metin değeriyle başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Metin imzasının metni. |

### Ayrıca Bakınız
* class [`TextSearchOptions`](/signature/python-net/groupdocs.signature.options/textsearchoptions/)
