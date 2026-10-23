---
title: "add विधि"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "मौजूदा MetadataSignature उदाहरण को संग्रह में जोड़ें।"
type: docs
url: /hi/python-net/groupdocs.signature.options/metadatasignoptions/add/
is_root: false
weight: 1010
---


## add {#metadata_signature}

मौजूदा MetadataSignature उदाहरण को संग्रह में जोड़ें।

```python
def add(self, metadata_signature):
    ...
```

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| metadata_signature | `MetadataSignature` | जोड़ने के लिए मौजूदा MetadataSignature इंस्टेंस। |

**Returns:** The MetadataSignOptions instance.

### उदाहरण

```python
from datetime import datetime
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSignOptions
from groupdocs.signature.domain import PdfMetadataSignature

with Signature("sample.pdf") as signature:
    options = MetadataSignOptions()
    options.add(PdfMetadataSignature("Author", "Mr.Scherlock Holmes"))
    result = signature.sign("signed.pdf", options)
    print(f"Signed with {len(result.succeeded)} metadata signature(s)")
```

### संबंधित देखें
* class [`MetadataSignOptions`](/signature/python-net/groupdocs.signature.options/metadatasignoptions/)
