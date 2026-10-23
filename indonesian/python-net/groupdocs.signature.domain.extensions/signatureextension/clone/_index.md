---
title: "clone metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mendapatkan salinan objek ini."
type: docs
url: /id/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Mendapatkan salinan objek ini.

```python
def clone(self):
    ...
```

### Contoh

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Kloning tanda tangan metadata dengan nilai baru
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Lihat Juga
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
