---
title: "to_date_time yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Meta veri imza değerini datetime.datetime tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_date_time/
is_root: false
weight: 1070
---


## to_date_time

Meta veri imza değerini bir `datetime.datetime`'a dönüştürür.

metadata değeri dönüştürülemezse bir istisna yükseltir. Orijinal değer string‑tabanlıysa, varsayılan kültür [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) üzerinden kullanılır.

```python
def to_date_time(self):
    ...
```

**Returns:** datetime.datetime: The metadata signature value as a `datetime.datetime`.

## to_date_time {#provider}

Meta veri imza değerini bir `datetime`'a dönüştürür.

Meta veri değeri dönüştürülemezse bir istisna fırlatır.

```python
def to_date_time(self, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** datetime: The metadata signature value as a `datetime`.

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
