---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "BarcodeSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/barcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

BarcodeSearchOptions sınıfının yeni bir örneğini varsayılan değerlerle başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature.options import BarcodeSearchOptions

# Varsayılan ayarlarla bir arama seçenekleri nesnesi oluşturun
options = BarcodeSearchOptions()
```

## __init__ {#encode_type}

BarcodeSearchOptions sınıfının yeni bir örneğini kodlama türü değeriyle başlatır.

```python
def __init__(self, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode kodlama tipini belirtir. |

## __init__ {#encode_type-text}

BarcodeSearchOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır.

```python
def __init__(self, encode_type, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| encode_type | `BarcodeType` | Barcode kodlama tipini belirtir. |
| text | `str` | Barcode imzasının Metnini ayarlayın. |

### Ayrıca Bakınız
* class [`BarcodeSearchOptions`](/signature/python-net/groupdocs.signature.options/barcodesearchoptions/)
