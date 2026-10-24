---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "FormField Signature örneğini klonlar."
type: docs
url: /tr/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

FormField Signature örneğini klonlar.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Örnek

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Yeni bir değerle bir metadata imzasını kopyala
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Ayrıca Bakınız
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
