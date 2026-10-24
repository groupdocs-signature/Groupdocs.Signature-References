---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Barkod imzası için varsayılan doğrulama seçeneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

Barkod imzası için varsayılan doğrulama seçeneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature.options import BarcodeVerifyOptions
from groupdocs.signature.domain import TextMatchType

options = BarcodeVerifyOptions()
options.text = "12345"
options.match_type = TextMatchType.CONTAINS
```

## __init__ {#text}

Doğrulama metni ile bir varsayılan doğrulama seçeneği başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Doğrulanacak barkod metni. |

## __init__ {#encode_type}

Barkod tipi doğrulaması ile bir varsayılan doğrulama seçeneği başlatır.

```python
def __init__(self, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barkod türü doğrulaması. |

## __init__ {#text-encode_type}

Barkod türü doğrulaması ve metin içeren varsayılan bir doğrulama seçeneğini başlatır.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Doğrulanacak barkod metni. |
| encode_type | `BarcodeType` | Barkod türü doğrulaması. |

### Ayrıca Bakınız
* class [`BarcodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/barcodeverifyoptions/)
