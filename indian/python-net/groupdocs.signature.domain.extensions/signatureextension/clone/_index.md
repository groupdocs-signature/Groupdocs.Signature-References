---
title: "clone मेथड"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.domain.extensions/signatureextension/clone/
is_root: false
weight: 1010
---


## clone

इस ऑब्जेक्ट की एक कॉपी प्राप्त करता है।

```python
def clone(self):
    ...
```

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignatures

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    # नए मान के साथ एक मेटाडाटा हस्ताक्षर को क्लोन करें
    author_sig = PdfMetadataSignatures.AUTHOR.clone("Mr. Sherlock Holmes")
    options.signatures.add(author_sig)
```

### संबंधित देखें
* class [`SignatureExtension`](/signature/python-net/groupdocs.signature.domain.extensions/signatureextension/)
