---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bir Metadata Signature örneğini klonlar."
type: docs
url: /tr/python-net/groupdocs.signature.domain/metadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Bir Metadata Signature örneğini klonlar.

```python
def clone(self):
    ...
```

**Returns:** Returns cloned Metadata Signature instance.

### Örnek

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Önceden tanımlanmış AUTHOR imzasına dayanarak yeni bir metadata imzası oluşturun
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

## clone {#value}

Verilen değerle Metadata Signature örneğini klonlar.

```python
def clone(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | `Any` | Yeni kopyalanmış nesne için değer. |

**Returns:** MetadataSignature: Cloned Metadata Signature instance with given value.

### Örnek

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Mevcut bir meta veri imzasını yeni bir değerle kopyala
author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ayrıca Bakınız
* class [`MetadataSignature`](/signature/python-net/groupdocs.signature.domain/metadatasignature/)
