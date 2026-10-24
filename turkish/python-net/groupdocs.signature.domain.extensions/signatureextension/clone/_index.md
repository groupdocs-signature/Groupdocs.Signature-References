---
title: "clone metodu"
second_title: "GroupDocs.Signature Python için .NET API Referansları"
description: "Bu nesnenin bir kopyasını alır."
type: docs
url: /tr/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Bu nesnenin bir kopyasını alır.

```python
def clone(self):
    ...
```

### Örnek

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Yeni bir değerle bir metadata imzasını kopyala
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Ayrıca Bakınız
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
