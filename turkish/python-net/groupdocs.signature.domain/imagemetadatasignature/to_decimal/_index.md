---
title: "to_decimal yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Decimal'a dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_decimal/
is_root: false
weight: 1090
---


## to_decimal

Decimal'a dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna yükseltilir. Orijinal değer metin tabanlıysa, [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresindeki varsayılan kültür kullanılır.

```python
def to_decimal(self):
    ...
```

**Returns:** decimal.Decimal: The Image Metadata Signature value as Decimal.

## to_decimal {#provider}

Meta veri imza değerini bir decimal'a dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna yükseltir.

```python
def to_decimal(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** float: The metadata signature value as a decimal.

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
