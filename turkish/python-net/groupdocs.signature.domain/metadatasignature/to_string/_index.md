---
title: "to_string yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata imzasını string tipine dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/to_string/
is_root: false
weight: 1180
---


## to_string

Metadata imzasını string tipine dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Diğer veri tipleri için varsayılan veri format sağlayıcısı kullanılacaktır.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value as a string.

## to_string {#format}

Metadata imzasını belirtilen formatı kullanarak string tipine dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Varsayılan kültür özelliği bilgisi SignatureSettings özelliklerinden [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresinden kullanılacaktır.

```python
def to_string(self, format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| format | `str` | Veri format dizesi. |

**Returns:** str: The metadata signature value as a string.

## to_string {#format-provider}

Belirtilen formatla string tipine dönüştürür.

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
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
