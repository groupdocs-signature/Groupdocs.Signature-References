---
title: "to_date_time yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imza değerini datetime tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/to_date_time/
is_root: false
weight: 1090
---


## to_date_time

Metadata imza değerini datetime tipine dönüştürür.

Meta veri değeri dönüştürülemezse, bir istisna yükseltilir. Orijinal değer metin tabanlı olduğunda, dönüşüm için [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresindeki varsayılan kültür kullanılır.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime: The metadata signature value as a datetime.

### Örnek

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    for metadata in result.signatures:
        try:
            dt = metadata.to_date_time()
            print(f"{metadata.name} as datetime: {dt}")
        except Exception as e:
            print(f"Could not convert {metadata.name} to datetime: {e}")
```

## to_date_time {#provider}

Metadata imza değerini datetime tipine dönüştürür.

```python
def to_date_time(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** datetime.datetime: The metadata signature value as a datetime.

Meta veri değeri dönüştürülemezse bir istisna fırlatır.

### Ayrıca Bakınız
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
