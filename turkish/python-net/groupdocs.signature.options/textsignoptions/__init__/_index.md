---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "TextSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/textsignoptions/__init__/
is_root: false
weight: 10
---


## __init__

TextSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#text}

TextSignOptions sınıfının yeni bir örneğini metinle başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | İmza metni. |

### Örnek

```python
from groupdocs.signature.options import TextSignOptions

# İstenen imza metniyle bir metin imza seçeneği oluşturun
options = TextSignOptions("John Smith")
```

### Ayrıca Bakınız
* class [`TextSignOptions`](/signature/python-net/groupdocs.signature.options/textsignoptions/)
