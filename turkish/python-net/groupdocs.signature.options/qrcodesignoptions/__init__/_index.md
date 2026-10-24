---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Varsayılan değerlerle QRCodeSignOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodesignoptions/__init__/
is_root: false
weight: 10
---


## __init__

Varsayılan değerlerle QRCodeSignOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

## __init__ {#text}

Belirtilen metinle bir QR kod imza seçenekleri örneğini başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | İmza metni. |

### Örnek

```python
from groupdocs.signature.options import QrCodeSignOptions

# İstenen metinle QR kod imza seçeneklerini oluşturun
options = QrCodeSignOptions("Approved by John Smith")
```

## __init__ {#text-encode_type}

Metinle QrCodeSignOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | QRCode metni. |
| encode_type | `QrCodeType` | QRCode kodlama türü. |

### Örnek

```python
from groupdocs.signature.options import QrCodeSignOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeSignOptions(
    "https://www.example.com/verify-document",
    QrCodeTypes.QR
)
```

### Ayrıca Bakınız
* class [`QrCodeSignOptions`](/signature/python-net/groupdocs.signature.options/qrcodesignoptions/)
