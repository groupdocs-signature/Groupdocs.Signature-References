---
title: "clone methode"
second_title: "GroupDocs.Signature for Python via .NET API-referenties"
description: "Haalt een kopie van dit object op."
type: docs
url: /nl/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Haalt een kopie van dit object op.

```python
def clone(self):
    ...
```

### Voorbeeld

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Kloon een metadata-handtekening met een nieuwe waarde
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Zie ook
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
