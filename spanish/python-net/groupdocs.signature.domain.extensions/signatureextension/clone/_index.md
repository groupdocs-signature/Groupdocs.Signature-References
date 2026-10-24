---
title: "clone método"
second_title: "Referencias de API de GroupDocs.Signature para Python a través de .NET"
description: "Obtiene una copia de este objeto."
type: docs
url: /es/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

Obtiene una copia de este objeto.

```python
def clone(self):
    ...
```

### Ejemplo

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # Clonar una firma de metadatos con un nuevo valor
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### Ver también
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
