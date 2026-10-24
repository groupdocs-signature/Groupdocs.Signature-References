---
title: "__init__ yapıcı"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "QR-Kod imzaları için doğrulama seçeneklerini başlatır."
type: docs
url: /tr/python-net/groupdocs.signature.options/qrcodeverifyoptions/__init__/
is_root: false
weight: 10
---


## __init__

QR-Kod imzaları için doğrulama seçeneklerini başlatır.

```python
def __init__(self):
    ...
```

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import QrCodeVerifyOptions

with Signature("signed.pdf") as signature:
    options = QrCodeVerifyOptions()
    options.text = "John"
    result = signature.verify(options)
    print(f"Verified: {result.is_valid}")
```

## __init__ {#text}

Belirtilen QR-kod metniyle QR-Kod imzaları için doğrulama seçeneklerini başlatır.

```python
def __init__(self, text):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Doğrulanacak QR-code metni. |

### Örnek

```python
from groupdocs.signature.options import QrCodeVerifyOptions

# Seçenekleri oluştur ve doğrulanacak QR-code metnini ayarla
options = QrCodeVerifyOptions()
options.text = "Approved by John Smith"
```

## __init__ {#text-encode_type}

Doğrulanacak metin ve QR-Kod kodlama türüyle QR-Kod imzaları için doğrulama seçeneklerini başlatır.

```python
def __init__(self, text, encode_type):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | `str` | Doğrulanacak metin. |
| encode_type | `QrCodeType` | Kodlama türü. |

### Örnek

```python
from groupdocs.signature.options import QrCodeVerifyOptions
from groupdocs.signature.domain import QrCodeTypes

options = QrCodeVerifyOptions(text="John Smith", encode_type=QrCodeTypes.QR)
```

### Ayrıca Bakınız
* class [`QrCodeVerifyOptions`](/signature/python-net/groupdocs.signature.options/qrcodeverifyoptions/)
