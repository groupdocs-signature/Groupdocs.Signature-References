---
title: "to_double yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imza değerini float tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/to_double/
is_root: false
weight: 1130
---


## to_double

Metadata imza değerini float tipine dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna yükseltilir. Orijinal değer metin tabanlıysa, [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresindeki varsayılan kültür kullanılır.

```python
def to_double(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_double {#provider}

Double tipine dönüştürür.

```python
def to_double(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** float: The metadata signature value as a float.

### Ayrıca Bakınız
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
