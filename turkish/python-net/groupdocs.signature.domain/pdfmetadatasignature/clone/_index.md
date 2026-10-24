---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Metadata Signature örneğini kopyalar."
type: docs
url: /tr/python-net/groupdocs.signature.domain/pdfmetadatasignature/clone/
is_root: false
weight: 1010
---


## clone

Metadata Signature örneğini kopyalar.

```python
def clone(self):
    ...
```

**Returns:** PdfMetadataSignature: Cloned Metadata Signature instance.

### Örnek

```python
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Yeni bir değerle standart bir meta veri imzasını klonlayın
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

## clone {#value}

Verilen değerle bir PDF meta veri imzası örneğini kopyalar.

```python
def clone(self, value):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | `Any` | Yeni klonlanmış nesne için değer. |

**Returns:** A cloned metadata signature instance.

### Örnek

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Mevcut bir meta veri imzasını yeni bir değerle kopyala
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ayrıca Bakınız
* class [`PdfMetadataSignature`](/signature/python-net/groupdocs.signature.domain/pdfmetadatasignature/)
