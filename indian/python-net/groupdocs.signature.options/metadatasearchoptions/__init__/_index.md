---
title: "__init__ कंस्ट्रक्टर"
second_title: "GroupDocs.Signature for Python via .NET API References"
description: "डिफ़ॉल्ट मानों के साथ MetadataSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।"
type: docs
url: /hi/python-net/groupdocs.signature.options/metadatasearchoptions/__init__/
is_root: false
weight: 10
---


## __init__

डिफ़ॉल्ट मानों के साथ MetadataSearchOptions क्लास का नया इंस्टेंस प्रारंभ करता है।

```python
def __init__(self):
    ...
```

### उदाहरण

```python
from groupdocs.signature import Signature
from groupdocs.signature.options import MetadataSearchOptions

with Signature("signed.pdf") as signature:
    result = signature.search([MetadataSearchOptions()])
    print(f"Found {len(result.signatures)} metadata signature(s)")
```

### संबंधित देखें
* class [`MetadataSearchOptions`](/signature/python-net/groupdocs.signature.options/metadatasearchoptions/)
