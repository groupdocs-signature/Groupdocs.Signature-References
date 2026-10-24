---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Varsayılan değerlerle QRCodeSearchOptions sınıfının yeni bir örneğini başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodesearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

Varsayılan değerlerle QRCodeSearchOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

## __init__ {#encode_type}

Kodlama türü değeriyle QRCodeSearchOptions sınıfının yeni bir örneğini başlatır.

```python
def __init__(self, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code kodlama türünü belirtir. |

## __init__ {#encode_type-text}

QRCodeSearchOptions sınıfının yeni bir örneğini kodlama türü ve metin değerleriyle başlatır.

```python
def __init__(self, encode_type, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| encode_type | `QrCodeType` | QR-Code kodlama türünü belirtir. |
| text | `str` | QR-Code imzasının metnini ayarla. |

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeSearchOptions

with Signature("signed.pdf") as signature:
    options = QrCodeSearchOptions()
    result = signature.search([options])
    print(f"Found {len(result.signatures)} QR code signature(s)")
```

### Ayrıca Bakınız
* class [`QrCodeSearchOptions`](/signature/python-net/groupdocs.signature.options/qrcodesearchoptions/)
