---
title: "to_string yöntemi"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Meta veri imza değerini bir string'e dönüştürür."
type: docs
url: /tr/python-net/groupdocs.signature.domain/imagemetadatasignature/to_string/
is_root: false
weight: 1170
---


## to_string

Meta veri imza değerini bir string'e dönüştürür.

```python
def to_string(self):
    ...
```

**Returns:** str: The metadata signature value.

## to_string {#format}

Meta veri imza değerini belirtilen formatı kullanarak bir string'e dönüştürür.

Bir boolean özelliği "True" veya "False" değerine dönüştürür. Varsayılan kültür bilgisi [`SignatureSettings.default_culture`](/signature/python-net/groupdocs.signature/signaturesettings/default_culture/) adresinden kullanılır.

```python
def to_string(self, format):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| format | `str` | Veri format dizesi. |

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

**Returns:** str: The metadata signature value as a string.

### Ayrıca Bakınız
* class [`ImageMetadataSignature`](/signature/python-net/groupdocs.signature.domain/imagemetadatasignature/)
