---
title: "to_single metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imza değerini float tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/to_single/
is_root: false
weight: 1160
---


## to_single

Metadata imza değerini float tipine dönüştürür.

metadata değeri dönüştürülemezse bir istisna yükseltir. Orijinal değer string‑tabanlıysa, varsayılan kültür [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) üzerinden kullanılır.

```python
def to_single(self):
    ...
```

**Returns:** float: The metadata signature value as a float.

## to_single {#provider}

Float tipine dönüştürür.

```python
def to_single(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** float: The Metadata Signature value as float.

### Ayrıca Bakınız
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
