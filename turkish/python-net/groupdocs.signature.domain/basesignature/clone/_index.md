---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "İmza örneğini klonla."
type: docs
url: /tr/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

İmza örneğini klonla.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Örnek

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Yeni bir değerle bir metadata imzasını kopyala
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Ayrıca Bakınız
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
