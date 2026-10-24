---
title: "to_decimal yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imza değerini Decimal tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/to_decimal/
is_root: false
weight: 1110
---


## to_decimal

Metadata imza değerini Decimal tipine dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna yükseltilir. Orijinal değer metin tabanlıysa, varsayılan kültür özelliği bilgisi [`SignatureSettings.DefaultCulture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresinden kullanılacaktır.

```python
def to_decimal(self):
    ...
```

**Returns:** The metadata signature value as Decimal.

## to_decimal {#provider}

Metadata imza değerini Decimal tipine dönüştürür.

```python
def to_decimal(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** The metadata signature value as Decimal.

### Ayrıca Bakınız
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
