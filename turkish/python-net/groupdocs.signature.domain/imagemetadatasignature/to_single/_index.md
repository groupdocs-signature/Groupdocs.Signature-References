---
title: "to_single metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Float tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_single/
is_root: false
weight: 1150
---


## to_single

Float tipine dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna fırlatır. Orijinal değer dize tabanlıysa, varsayılan kültür özelliği bilgisi [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) üzerinden kullanılacaktır.

```python
def to_single(self):
    ...
```

**Returns:** float: The Image Metadata Signature value as float.

## to_single {#provider}

Metadata imza değerini float tipine dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna yükseltir.

```python
def to_single(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** float: The metadata signature value as a float.

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
