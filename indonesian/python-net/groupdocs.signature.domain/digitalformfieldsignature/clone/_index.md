---
title: "clone metode"
second_title: "Referensi API GroupDocs.Signature untuk Python melalui .NET"
description: "Mengkloning instance FormField Signature."
type: docs
url: /id/python-net/groupdocs.signature.domain/digitalformfieldsignature/clone/
is_root: false
weight: 1010
---


## clone

Mengkloning instance FormField Signature.

```python
def clone(self):
    ...
```

**Returns:** DigitalFormFieldSignature: Cloned FormField Signature instance.

### Contoh

```python
from groupdocs.signature.domain import PdfMetadataSignatures

# Kloning tanda tangan metadata dengan nilai baru
author_signature = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
```

### Lihat Juga
* class [`DigitalFormFieldSignature`](/signature/python-net/groupdocs.signature.domain/digitalformfieldsignature/)
