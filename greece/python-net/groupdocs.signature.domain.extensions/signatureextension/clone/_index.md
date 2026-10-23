---
title: "μέθοδος clone"
second_title: "GroupDocs.Signature για Python μέσω .NET Αναφορές API"
description: "Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου."
type: docs
url: /el/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Λαμβάνει ένα αντίγραφο αυτού του αντικειμένου.

```python
def clone(self):
    ...
```

### Παράδειγμα

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Κλωνοποίηση μιας υπογραφής μεταδεδομένων με μια νέα τιμή
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Δείτε επίσης
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
