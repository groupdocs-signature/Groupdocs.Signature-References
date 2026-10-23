---
title: "méthode clone"
second_title: "Références API de GroupDocs.Signature pour Python via .NET"
description: "Obtient une copie de cet objet."
type: docs
url: /fr/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Obtient une copie de cet objet.

```python
def clone(self):
    ...
```

### Exemple

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Cloner une signature metadata avec une nouvelle valeur
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Voir aussi
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
