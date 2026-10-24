---
title: "to_double yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Float'a dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_double/
is_root: false
weight: 1110
---


## to_double

Float'a dönüştürür.

metadata değeri dönüştürülemezse bir istisna yükseltir. Orijinal değer string‑tabanlıysa, varsayılan kültür [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) üzerinden kullanılır.

```python
def to_double(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as a float.

## to_double {#provider}

Metadata imza değerini float tipine dönüştürür.

Belirtilen format veri sağlayıcısını kullanarak dönüşümü gerçekleştirir.

```python
def to_double(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** float: The metadata signature value as a float.

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
