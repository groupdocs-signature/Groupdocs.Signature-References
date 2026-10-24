---
title: "to_string yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Geçersiz kılınmış ToString yöntemi kullanarak meta veri imzasını bir dizeye dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/certificatemetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Geçersiz kılınmış ToString yöntemi kullanarak meta veri imzasını bir dizeye dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Diğer veri tipleri için varsayılan veri formatı sağlayıcısı kullanılır.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Belirtilen formatta bir dizeye dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür.

```python
def to_string(self, format, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| format | `str` | Veri format dizesi. |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** The metadata signature value as a string.

### Ayrıca Bakınız
* class [`CertificateMetadataSignature`](/signature/python-net/groupdocs.signature.domain/certificatemetadatasignature/)
