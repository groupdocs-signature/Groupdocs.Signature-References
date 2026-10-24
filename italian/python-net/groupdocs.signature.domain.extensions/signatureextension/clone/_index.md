---
title: "metodo clone"
second_title: "GroupDocs.Signature for Python via .NET Riferimenti API"
description: "Ottiene una copia di questo oggetto."
type: docs
url: /it/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Ottiene una copia di questo oggetto.

```python
def clone(self):
    ...
```

### Esempio

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Clona una firma metadata con un nuovo valore
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Vedi anche
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
