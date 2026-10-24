---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "BarcodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSignOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#text}

BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Barkod metni. |

### Örnek

```python
from groupdocs.signature.options import BarcodeSignOptions

# İstenen metinle barkod imza seçenekleri oluşturun
options = BarcodeSignOptions("JohnSmith")
```

## __init__ {#text-encode_type}

BarcodeSignOptions sınıfının yeni bir örneğini metinle başlatır.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Barkod metni. |
| encode_type | `BarcodeType` | Barkod kodlama türü. |

### Örnek

```python
from groupdocs.signature.options import BarcodeSignOptions
from groupdocs.signature.domain import BarcodeTypes

# Metin ve tür ile barkod imza seçenekleri oluşturun
options = BarcodeSignOptions("JohnSmith", BarcodeTypes.CODE128)
```

### Ayrıca Bakınız
* class [`BarcodeSignOptions`](/signature/python-net/groupdocs.signature.options/barcodesignoptions/)
