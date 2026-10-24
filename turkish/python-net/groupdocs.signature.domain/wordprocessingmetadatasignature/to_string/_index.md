---
title: "to_string yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imzasını string tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/to_string/
is_root: false
weight: 1030
---


## to_string

Metadata imzasını string tipine dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Diğer veri tipleri için varsayılan veri formatı sağlayıcısı kullanılır.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Meta veri imzasını belirtilen formatta bir dizeye dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür.

```python
def to_string(self, format, provider):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| format | `str` | Veri format dizesi. |
| provider | `System.IFormatProvider` | Veri dönüştürme işlemlerinde kullanılacak format veri sağlayıcısı. |

**Returns:** str: The metadata signature value as a string.

### Ayrıca Bakınız
* class [`WordProcessingMetadataSignature`](/signature/python-net/groupdocs.signature.domain/wordprocessingmetadatasignature/)
