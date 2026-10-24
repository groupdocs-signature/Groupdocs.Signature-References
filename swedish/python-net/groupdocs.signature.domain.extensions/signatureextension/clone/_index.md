---
title: "clone metod"
second_title: "GroupDocs.Signature för Python via .NET API-referenser"
description: "Hämtar en kopia av detta objekt."
type: docs
url: /sv/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Hämtar en kopia av detta objekt.

```python
def clone(self):
    ...
```

### Exempel

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Klona en metadata‑signatur med ett nytt värde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Se även
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
