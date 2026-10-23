---
title: "clone metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Duplikat instance tanda tangan."
type: docs
url: /id/python-net/groupdocs.signature.domain/basesignature/clone/
is_root: false
weight: 1010
---


## clone

Duplikat instance tanda tangan.

```python
def clone(self):
    ...
```

**Returns:** The cloned `Signature` instance.

### Contoh

```python
    from datetime import datetime
    from groupdocs.signature.domain import PdfMetadataSignatures

    # Kloning tanda tangan metadata dengan nilai baru
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    ```

### Lihat Juga
* class [`BaseSignature`](/signature/python-net/groupdocs.signature.domain/basesignature/)
