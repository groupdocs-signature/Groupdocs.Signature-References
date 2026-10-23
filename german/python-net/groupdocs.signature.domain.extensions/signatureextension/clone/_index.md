---
title: "clone-Methode"
second_title: "GroupDocs.Signature für Python über .NET API-Referenzen"
description: "Gibt eine Kopie dieses Objekts zurück."
type: docs
url: /de/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Gibt eine Kopie dieses Objekts zurück.

```python
def clone(self):
    ...
```

### Beispiel

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Klonen Sie eine Metadaten-Signatur mit einem neuen Wert
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Siehe auch
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
